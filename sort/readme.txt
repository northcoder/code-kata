==============================================================
���������� ���������
==============================================================


��� �������� �����: 	input.txt
��� ��������� �����: 	output.txt
����������� �� �������: 	2 �������
����������� �� ������: 	256 ��������

��� ������ ����� �����. ���� ������ � ������������� ��� � ������� ���������� � ������� ���������� ���������.

���������� ��������� ���������� �� ���� ��������� ������� �� ������� �������� � ������� (������ �������) ��� ������� �������� ���������� ��� ����� � �������������� ��� ��������������� ����� ������� � ��������� ��� �� ��� ����� (��������, ������� ��������� �������� �� ���� ������ ������). ����� �����������������, ��� �� ����������� ������ ���������� ���������, �� �������� ��� ��� ������� �������� �������, ����� ����, ��� �� ����� ���������, �������� ��� ����� ������.

========= ������ �������� ����� =========

� ������ ������ �������� ����� ���������� ����� n
(1 <= n <= 1000) � ����� ��������� � �������. �� ������ ������ ��������� ��������� ����� �����, �� ������ �� ������������� 10^9.

========= ������ ��������� ����� =========

� ������ ������ ��������� ����� �������� n
�����. ��� ���� i-�� ����� ����� �������, �� �������, � ������ ��������� ��� ����������� ���������, ��� ��������� i-�� ������� ��������� �������. ������� ����������, ������� � �������. ����� ������ ����� ������� ������ ������ ����� ���� ������.

�� ������ ������ ��������� ����� �������� ��������������� ������. ����� ������ ����� ������� ������ ������ ����� ���� ������.


========= ������ =========
input.txt
10
1 8 4 2 3 7 5 6 9 0 
	
output.txt
1 2 2 2 3 5 5 6 9 1
0 1 2 3 4 5 6 7 8 9

����������� � �������

� ������� ���������� ��������� �������� ��������� �������:

1. ������ ������� �������� �� ����� �����, ������� ������ ����� � ������ � �������. ��������������� ����� �������: [1]
2. ������ ������� ������ �������, ������� �� ���� �������� �� ����� �����, � ������ ����� � ������ � ������. [1 8]
3. �������� ������ ���������, ������� �������� ������ �����. [1 4 8]
4. ������ �������� ������ �����. [1 2 4 8]
5. ������ �������� ������ �����. [1 2 3 4 8]
6. ������� �������� ����� �����. [1 2 3 4 7 8]
7. ������� �������� ����� �����. [1 2 3 4 5 7 8]
8. �������� �������� ������ �����. [1 2 3 4 5 6 7 8]
9. ������� �������� ������� �����. [1 2 3 4 5 6 7 8 9]
10. ���� �������� ������ �����. [0 1 2 3 4 5 6 7 8 9]