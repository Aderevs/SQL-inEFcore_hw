# LINQtoEntities_hw

---
�������� 1
-
³������ �������� 2 (3 �����) �� ���������� �������� �������� ��������.

����� �� ���� ���� "����" ����, ���� �� ������ ��������������� ������� � ����, �� ������� ��� ������� ��������. �� ������ ��������������� ���� ��������� ���� ���������� � ���������� ICategoryRepository, IKeyParamsRepository, IProductRepository �� ���� (�� � � ���� ������ CRUD � ����).

³������� �������� BLL ����� Services �� �� ������� ����� UserServices :

* ��������� ���������� ����� ��������� (��� �� ���������� NotImplementedException � ���� ������ �� ������).
* ������ ���������� ����� ProductsByWord � ���� ProductServices. �������� �����, ������ ���� ���������� ������ ������ �� ������ ��������
* ������ ���������� ����� GetProductsByCategoryAndPrice � ���� ProductServices. �������� �����, ������ ���� ���������� ����� ������ �������� �� �� �������� �� ����� � ������� �������
* ������ ���������� ����� GetProductsByCategoryAndKeyWordsWithPrice � ���� ProductServices. �������� �����, ������ ���� ��������� ��������� �� �� �������� ������

ϳ��� ��������� ���������� ������ �� ��������� ���������, � ����� ������������ ������� �������

---
�������� 2
-
³������ �������� 1 (����� �����).

³������� �������� BLL ����� Services

���������� ����� GetCategoryInfoByName � ���� CategoryServices. � ����� ������� ��������� ���������� �� �������, ����� ���������� ��������:

1) ����������� ����
2) ̳�������� ����
3) �������
4) ������ ����� �� �������� ������� � ������ Dictionary

���� ���� ���������� Dictionary �� ������ ����������� Header � ������ ����� Word, � ������� ������� �� �������� KeyWord �� �������� Header

������� �� ��������� �������� ��� ���������� CategoryInfo
������ � ���� ���� ��������, ������ ����� �� ������� ������ ����� (����� ������� ���� ��������� �� ��� ������)
![Image from hw](https://lms.cbs.com.ua/pluginfile.php/25432/mod_assign/intro/screen.png)
���� ��� ��������� �� �������� �� ������� ������� ������� � ������ ��������� ������� �� ������� �������� ��������� �� ����. 

---
�������� 3*
-
³������ �������� 2 (����� �����).

³������� �������� BLL ����� Services

* � ����� ProductsByWord � ���� ProductServices ������ ����. �������� �����, ������ ���� ���������� ������ ������ �� ��������� ������� ������ �� ������

* ���� ��� ��������� �� �������� ����� ����� ����������