������: �������� � ��������: �������� ������

��������-������� ǂ ���� ����� ������� ������ ������: ��� �����, ��� ����, ������ ������� �������, ��������� � ���� ��������. ����� �������� �� ������� ������ �������, ��� ���������� ����������� ������ ���������. ���������� ����� �������� ��� �� ��� ����������: � �������� � ��� ����� ������� ����� ������� ���������.
���������� ����������� �������, ������� �������� ����������������� ����������� ���������� ��������, ����� ��������� �� �������������� ����������.
������������� ������ � ��������� �����.
	�	market_file.csv�- �������� ������ � ��������� ���������� �� �����, � ������������� � ����������� � ��� ����������� ���������.
	?	id�� ����� ���������� � ������������� ���� ������.
	?	�������������� ������������ ������������ ����� �������������� ���������� (������� �������): ����������� ��� �������� ��������.
	?	��� ��������� ������� �������, �������� ��������� � ����������.
	?	��������� ���������� ���������� � ���, ����� �� ��������� ���������� �������������� ����������� � ������. �������� �� ��� ���� ����������.
	?	������_�����_6_����� �������������� �������� ������������� ������������ ��������, ������� ����������� �� ���������� �� ��������� 6 �������. ��� �������� ����������, ����� ����� ��������, �������, ������� ������� � ������� ����������� �� �������.
	?	������_�����_���_����� ���������� ������������� ������������ � ������� ������.
	?	�������������� ��������, ������� ����������, ������� ���� ������ � ������� ����������� ���������� �� �����.
	?	���������_��������� �������������� ���� ������� �� ����� �� ������ ����� ������� �� ��������� 6 �������.
	?	����������_����������� ����� ���������� ��������� ������� � ���������� �� ��������� 6 �������.
	?	�������_��������_���������_��_������� ����������, ������� � ������� ��������� ���������� ���������� �� ����� � ������� ���������� ������. ������������_��������_����_������� � ����� ����� ������������ ������� � ������� �� ��������� 3 ������.
	?	������_��������� ����� �����, ������� ��������� ���������� �� ����� ��������� �����.
	?	�������_��_������� ������� ���������� �������, ������� ���������� ���������� �� ���� ����� �� ���� �� ��������� 3 ������.
	�	market_money.csv�- � ������� � �������, ������� �������� ������� � ����������, �� ���� ������� ���������� ����� �������� �� ������ �������������� � ������.
	?	id�� ����� ���������� � ������������� ���� ������.
	?	�������� �������� �������, �� ����� �������� ������������� �������. ��������, '�������_�����' ��� '����������_�����'.
	?	��������� ����� ������� �� ������.
	�	market_time.csv�- � ������� � ������� (� �������), ������� ���������� ������ �� ����� � ������� �������.
	?	id�� ����� ���������� � ������������� ���� ������.
	?	�������� �������� �������, �� ����� �������� ������������� ����� �����.
	?	������� �������� �������, ������������ �� �����, � �������.
	�	money.csv�- � ������� � �������������� ������� ���������� �� ��������� 3 ������: ����� ������� �������� ������� �� ������ ������� ����������.
	?	id�� ����� ���������� � ������������� ���� ������.
	?	��������� �������� �������.
�������� ������ �� ��� �����:
	1	����������� ������, ������� ���������� ����������� �������� �������������� ����������.
	2	������� ������� �����������, �������������� ��� � ���������, ��� ��������� ��� �������������� ����������, ��������� ������ �������������, ������ � ������� ����������� � �������� ������ (���� �����������). ��������� ��������:
	�	������ �������� � ������������ ����� ������� �� ����� � ������� ������������ �������� �������������� ����������.
	�	������ ��������, ������� �������� ������ �������, �� ���� ������ � ������� ��������� ������.
	�	������ ��������, ������� �������� ������ �� ��������� ǒ����� ��� ����� (����� ���������, ������� ����� �������� �� ������ �������) ��� ǒ����� ��� ������.
	�	������ �������� � ������� ������������ �������� �������������� ���������� � �������� ������� �������������.


� ���� ������������ ��������� ��������� �����:

������������� ������
1. ����������� ��������� �������� ��������:
* ������� � �������� ������
* ������ �������� �� �������������
2. ��market_file
* � �����������_��������������������������������� �����������
3. ��market_money
* � ����������������������������������_�������������� �������������_�����
4. ��market_time
* � ��������������������������������_�������������� �������������_�����

������ ������ � ����������
* �������� ����������������� ������ ������.
* ��������� ���������� � ����������� ������.
* ��� ������ ������ ������ ��� �������� �������������� ������ ������ ��� ���������� ��������������������.
* ������������ ��������� ��� ������ ������ ������ � ������ � �������������� ������.

������ ������
��������� ������� ���� ���������� LogisticRegression(C=1, penalty='l1', random_state=42, solver='liblinear'). ������� roc_auc ��� �������� ������� �������� ��������� 0.917.

������ � ������������ ��������
�������� �������� ��������, �� ������� ������� �������� �������� ��� ���������� �������������� ���������� (�� �������� ����������):
* ���������_�������
* �������_��������_���������_��_�����
* �������_��_�����
* �����_����������_�����
* �����_�������_�����
* ������_�����_6_���
�������� ������ ��������:
* ���������_��������
* ������_�������
* ������������
* ���_�������
* ������_�����_���_���
C������ ����� ������ �� ������� ���������� �������������� ��������, ����������� �������������� ������������ � ������ (����� �� �����, ���������� ��������������� ��������� � �������), � ��� �� ����� ��������, �������, ������� ������� �� 6 �������. ���������� �������� ���� ����������� �������� ����������� �������� �������������� ���������� �������.
��������, ����������� ���������� � ����������� ��������� ������� (��������� �������) ����� ������ �� ��������������� �������� ������������� ����������. ����� ������� ������ ��, ��� ���������� ������������ ����������������_�������_�������_�_�������������������� ������ � ����������� �������� (0).

�������� ����������� � ������������

������� ����������� � ������� ����� ��������� �������
� ���� �������� ����������� �������� �������������� ����������. � ��������� �������� ���������_������� ����� ����� 0.6 ���������� ������ ������� �������� �� �����, ����� ������ ������������ ������� � �������, ������ ������� ��������� � �������, � ��� �� �� ��� ���������� ������� ���������� ������������� ������������.
* ����� ��������� ������������� ������������ ��������, ���������� �� ��������� ������ � ��������� ��������� ��������.

������� ����������� � ���������� ���������� "������ ��� �����"
� ���� �������� ����� ����������� ������������ �������� �������������� ����������. ������ ������� � �������� �������� �� �����, ������������� ���� ������� � �������� ������ ������� �� �����, ��� ����������, � ������� ���������� �������� �� ������� ������. �� ������ ������� ����������� ��������� ������� ������� � ��������� ������ ��������� �������.
* ����� ��������� ����������� ��������� ������� ��� ������� ������������ ������� ��� ���������� ���������� ���������� �������.

