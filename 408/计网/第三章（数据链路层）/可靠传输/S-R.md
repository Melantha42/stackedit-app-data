


# 选择重传协议
![输入图片说明](/imgs/2025-07-24/rWqrzQavkf4ayY72.png)

### 若接收窗口>发送窗口，出现低效传输，因为该协议边接收边确认边滑动窗口，不同于GBN累积发送，一般情况取接发窗口相等
## 数据帧丢失
### 采用超时重传机制，接收窗口始终不滑出未接收帧位，超时未收到该帧位ACK则重传，此时其他帧位照常发送，极大提升了传输效率
![输入图片说明](/imgs/2025-07-24/towK5dNgESNmwsLG.png)
## 数据检查错误
### 采用NAK，接收方主动请求重传错误帧位并丢弃错误帧
![输入图片说明](/imgs/2025-07-24/kht6fSLNB4IEb58b.png)
### 发送方在计时器触发之前重传错误帧，重置计时器
![输入图片说明](/imgs/2025-07-24/hFRu3QWJzgEzmCeG.png)
<!--stackedit_data:
eyJoaXN0b3J5IjpbNzkzMTY1MjE2LDM3NDY3NjYxM119
-->