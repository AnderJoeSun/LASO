---
layout: post
title: UART ������ - ���ڿ������ṹ
---

## ���ڿ���������
UART Controller (p853-p882)
	������һ����������Ҫ�˽�����->���룬��������ʵ��
		1. �����Timing (����ͨ��ʵ��ʱ��ͼ)
			Serial I/O Frame Timing Diagram (Normal UART)  ->p860
		2. ���룺SFR (���ڿ������ļĴ���)
			REGISTER DESCRIPTION  ->p864
		3. ʵ�֣�Block Diagram (�ṹ��ͼ)
			Block Diagram of UART  ->p854
## ���ڿ������ṹ			
	Block Diagram:
		Peripheral Bus ��������
			*(int *)SFR_ADDR = value;
		Controll Unit ���Ƶ�Ԫ
			Control Regs
		Baud-Rate Gengenrator �����ʷ�����
			Clock Source ʱ��Դ (66M)
		Transmitter ������
			Transmit shift ������λ��
			Transmit buffer ���Ͷ���FIFO������
		Receiver ������
			Receiver shift ������λ��

	

<br> <br> 
<div> <a href="chp5-3.html">��һ��</a> &nbsp;&nbsp; | &nbsp;&nbsp; <a href="chp5-5.html">��һ��</a> </div> <br> <br>