


# 后退N帧协议
![输入图片说明](/imgs/2025-07-24/PJgicuJF1BcArkf1.png)
## 接发窗口大小不统一，需要给帧编号排序 ，2bit信息对应二进制的4种状态
![输入图片说明](/imgs/2025-07-24/nqhtEj6EcPV5pheD.png)
## 正常接收情况下，只需返回最后一帧确认帧ACK_i，表示已收到来自i号帧之前的所有帧，发送窗口后移，开始下一轮发送
![输入图片说明](/imgs/2025-07-24/OQQF6db2I5v88Avf.png)

## 异常情况下，从哪里丢帧从哪里后退帧使其重传，重传完成后将计时器重置

![输入图片说明](/imgs/2025-07-24/lTdmf5bONfGW6n31.png)
![输入图片说明](/imgs/2025-07-24/f66AxNR8ePucWPN8.png)
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE5Nzc2NzcyODgsLTE3NzM4Mjg2Nyw3Nj
U0MzQ2MDFdfQ==
-->