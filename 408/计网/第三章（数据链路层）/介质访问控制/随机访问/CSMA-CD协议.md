
# 有线传输协议CD

![输入图片说明](/imgs/2025-07-27/xEpdEHYtZENezuQU.png)
![输入图片说明](/imgs/2025-07-27/tlLrJdvotNdv9VIC.png)

## 概要
![输入图片说明](/imgs/2025-07-27/jiOvg68C89MuVlOP.png)
![输入图片说明](/imgs/2025-07-27/PkiBeOCgC8ERBsjl.png)

### 边发边监听，有冲突则根据冲突次数采用截断二进制退避算法重发
![输入图片说明](/imgs/2025-07-27/xrcLkesxCakJst8t.png)

### 怎么衡量争用期
![输入图片说明](/imgs/2025-07-31/5uOiEVCEQaKqHYrf.png)
![输入图片说明](/imgs/2025-07-31/4gGZJZG8HcmI18do.png)

### 最短帧长限制
![输入图片说明](/imgs/2025-07-31/BAkmKPvUL6shoOS8.png)
![输入图片说明](/imgs/2025-07-31/9VfDKBXVNwvLDa9b.png)
![输入图片说明](/imgs/2025-07-31/iJkojHF6LUQxt3yS.png)
作用：保证发送结点是处于完全占用信道的情况下发送的数据，否则当其余结点收到小于最短帧长限制的帧时，会当作非法帧（不完整）丢弃。
即：

![输入图片说明](/imgs/2025-07-31/TByfDLO0DiPNnaHp.png)

### 最长帧长限制
![输入图片说明](/imgs/2025-07-31/cWzQLb8LiIlmdM5u.png)

### 补充
![输入图片说明](/imgs/2025-07-31/nD1hTjyXoWav1De4.png)

![输入图片说明](/imgs/2025-07-31/Lkt8FmMmFmH7Vz1u.png)
因为CSMA/CD协议用于有线网络传输，其传输率趋于稳定，不考虑干扰情况，则没有冲突=帧完整
<!--stackedit_data:
eyJoaXN0b3J5IjpbODU4NDAxODQzLDExMzYzOTM4NDksNDYyND
I3NzQ3LDEzOTQwOTA1MTMsLTE0MDgyNTg5ODhdfQ==
-->