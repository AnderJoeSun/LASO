---
layout: post
title: UART ������ - ����Ӳ������
---

## ���ڵ�Ӳ������ (Ӳ��ԭ��ͼ)
	COM0 �ӿ� DB9 ���빫ͷ
	pin2: RSRXD0
	pin3: RSTXD0
	pin5: GND
	ͨ�� TxD �����ַ������ֽ�Ϊ��λ 5-8bits��
	ͨ�� RxD �����ַ������ֽ�Ϊ��λ 5-8bits��

	RS232 ��ƽ��-15v->+15v (+15v-�߼�0, -15v-�߼�1)
	TTL ��ƽ�� 0->+5v (0-�߼�0, 5v-�߼�1)
	�߼���ƽ��ת���� MAX3232 (����оƬ)

	�鿴 MAX3232 оƬ+���İ�ԭ��ͼ�ɵ�
		RSTXD0 <- XuTxD0 -- TINY1B B7 -- XuTXD0/GPA0_1
		RSRXD0 -> XuRxD0 -- TINY1B B8 -- XuRXD0/GPA0_0

	���ۣ� GPA0 ������ UART �� Txd/Rxd ��������
	

<br> <br> 
<div> <a href="chp4-4.html">��һ��</a> &nbsp;&nbsp; | &nbsp;&nbsp; <a href="chp5-2.html">��һ��</a> </div> <br> <br>