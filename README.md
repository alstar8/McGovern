# � ������ ���� ���������� �������� �� ������ Automatic Discovery of Subgoals inReinforcement Learning using Diverse Density:

https://scholarworks.umass.edu/cgi/viewcontent.cgi?article=1017&context=cs_faculty_pubs

� mcgovern.py ������� ��� ������, ����� Game � ��������� �����, � ����� agent � ��������� ���������� � ������� ������

## ����������� ������ �������� ����� train.py

��� ��� �������� ����� ���������� �������� � �����������, ���������� � train.py, ��� ������� �� ����� ��������.
��� �������� ��������� ���� "Grid World", ��� ������������ ������� ������ ��������.

������ ������������ ����, ���� ������ ������ �����, ������� �������, ������� ��������� ����� Diverse Density.

����� ������������ ��� �����.

� ������� ������� ��������� ���� 4 3 position [0, 1, 2, 3] [-0.18281843807147813, -0.18395445100610527, -0.17562076331583998, -0.18189855164936664] 
��� 4 3 position ��� ������� ������� ������, [0, 1, 2, 3] ��� ��� ��������� �������� �� ���� ������� � ��������� ������ �������� Q-values, ������ �� ������� � ���������� ��������� ��������

�������� 0 - �����
	 1 - ����
	 2 - �����
	 3 - ������


� train.py ��� �������� ������ � ������ 10 �� 10 (����� ��������� �����) ��������� 

	ag = agent(10,10)

����� ���� ������� ������, ��� ����������� 3 �����������, 1 - �� ����� ������ ��� ������ 2 - � ����� ������� ���������� �������, 3 - �� ����� ������� ������������� �������

	ag.stenka(5,4,6)

����� �������� ���������� ���� 
	
	ag.tcel(8,8)

����� ����� ���������������� ��������� �������� Q-table ��� ���� ��������� �����

	ag.init2()

����� ����� ����� ag ����� ��� ����������� ��������
