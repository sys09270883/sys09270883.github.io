---
title: "[Django] Pycharm���� Django ������Ʈ �����ϱ�"
excerpt: "Pycharm Community Edition���� Django �����ӿ�ũ ������Ʈ ����"
toc: true
toc_sticky: true
categories: [Web]
tags: [Web, Django, Python, Pycharm, Pycharm Community Edition]
---

Pycharm Community Edition���� Django ������Ʈ�� ������ ����.

## 1. Pycharm���� �� ������Ʈ�� ����
�� ������Ʈ�� �����.

<!-- ![]({{ site.url }}{{ site.baseurl }}/assets/images/[Django.1-1].png ){: .align-center} -->

## 2. ���������� ���
�� ������Ʈ�� ���������͸� ����ؾ� �Ѵ�. <br>
���������͸� ����ϴ� ����� 2������ �ִ�.
1. �� ������Ʈ���� ����ȯ���� ���� �� Django�� pip���� ��ġ
2. �̸� ����ȯ���� ����� Django�� ��ġ�� �� ������Ʈ���� �ش� ����ȯ���� ���

1�� ������� �� ������Ʈ�� ���������͸� ��������.

<!-- ![]({{ site.url }}{{ site.baseurl }}/assets/images/[Django.1-2].png ){: .align-center} -->

## 2-1. Django ��ġ
�� ������Ʈ�� Django�� ��ġ�� ����. <br>
File�� Settings(Ctrl + Alt + S)�� ������. <br>

<!-- ![]({{ site.url }}{{ site.baseurl }}/assets/images/[Django.1-3].png ){: .align-center} -->

Install(Alt + Insert)�� ���� Django ��Ű���� ��ġ�Ѵ�. <br>

<!-- ![]({{ site.url }}{{ site.baseurl }}/assets/images/[Django.1-4].png ){: .align-center} -->

<!-- ![]({{ site.url }}{{ site.baseurl }}/assets/images/[Django.1-5].png ){: .align-center} -->

## 3. Django ������Ʈ ����
Alt + F12�� ���� �͹̳��� Ų �� Django ������Ʈ�� �����Ѵ�. <br>

`django-admin startproject temp`
> `temp` ������Ʈ ������

<!-- ![]({{ site.url }}{{ site.baseurl }}/assets/images/[Django.1-6].png ){: .align-center} -->

�� ����ó�� temp ������ �����ȴ�. temp ���� �ȿ� �� ���� temp ��� �⺻ �۰� manage.py�� �ִ�. <br>
manage.py�� Django ������Ʈ���� ����� ��ɾ���� ���� �����̶�� �����ϸ� �ȴ�. <br>

<!-- ![]({{ site.url }}{{ site.baseurl }}/assets/images/[Django.1-7].png ){: .align-center} -->

## 3-1. Django Application ����
temp ������ �̵��� �� �͹̳ο� ������ ���� �Է��Ѵ�. <br>

`python manage.py startapp tempApp`
> `tempApp` Application ������

<!-- ![]({{ site.url }}{{ site.baseurl }}/assets/images/[Django.1-8].png ){: .align-center} -->

## 4. ��������
�͹̳ο��� ������ ������ ����. <br>

`python manage.py runserver`
> �⺻ 8000 ��Ʈ�� ������ ����ȴ�. ����� ���� ��Ʈ�� �� ���� �ִ�.

<!-- ![]({{ site.url }}{{ site.baseurl }}/assets/images/[Django.1-9].png ){: .align-center} -->

localhost:8000�� �����Ͽ� ������ ���� ȭ���� �߸� ���������� ������ ����� ���̴�.

<!-- ![]({{ site.url }}{{ site.baseurl }}/assets/images/[Django.1-10].png ){: .align-center} -->

������ Ctrl + C�� �� �� �ִ�. /