---
layout: post
title: UART ������ - ���ڹܽŹ��ܸ���
---

## ���ڵĹܽŹ��ܸ��� 
�ο� S5PV210оƬ�ֲ�
	GPA0 Mux Function
	�鿴 GPA0[0] GPA0[1]��ȷ���� UART �ĸ��ù���
	�鿴 GPA0CON �Ĵ������˽�������� (0010)
	GPA0CON : ��ַ 0xe0200000
	[FriendlyLEG-TINY210]# md 0xe0200000
	e0200000: 22222222 000000ab 00005555 00000000    """"....UU......
	e0200010: 00000000 00000000 00005555 00000000    ........UU......

	[FriendlyLEG-TINY210]# mw 0xe0200000 0x22222202

	���ۣ�RXD Ӱ����գ� TXD Ӱ�췢��
		RTS��CTS�Է��ͺͽ�����ʱ��Ӱ�죨�������ƣ�

	

<br> <br> 
<div> <a href="chp5-1.html">��һ��</a> &nbsp;&nbsp; | &nbsp;&nbsp; <a href="chp5-3.html">��һ��</a> </div> <br> <br>