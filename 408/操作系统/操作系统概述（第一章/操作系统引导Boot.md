


![输入图片说明](/imgs/2025-07-26/2FyYVRE6tAZqBVmE.png)
![输入图片说明](/imgs/2025-07-26/wixcZ0MHa86UemVS.png)
![输入图片说明](/imgs/2025-07-26/4DkZ43yVqvFPrxxq.png)


# 硬盘的主引导扇区-MBR
硬盘的主引导扇区（[Master Boot Record, MBR](https://www.google.com/search?sca_esv=a41ed8ea23771f3d&rlz=1C1CHZN_en__1128__1128&cs=0&sxsrf=AE3TifNX08V7R_tsNQemhjWZGIwXDxtcug%3A1757570558543&q=Master+Boot+Record%2C+MBR&sa=X&ved=2ahUKEwjr8KjGhNCPAxXjm68BHZRdAZkQxccNegQIDBAB&mstk=AUtExfDU3vyoCeUfwPFa6PKAwVRH8ctc4ITWZLuoZ3mTNiYLzG2TL7PZh0OeOr8g8MiLvqJwMOLEeov5oauahE431a49IRTkZiIjSPtoVp-P7Qd3HOGMOCnJvxCmhf6Nva8iCPiv5ngTb6oRYAjOQAchcW0bx6Gu1Xjocv1hUm2NcCZ8FQvoLJdW9B7dzkJRw0VV-HJnKxHxvKKjuakXUt_oxH_nzD_Phwytzq5GuLEqBeDw6LA_3pgtBsmeDctwk4Q4fjeXcVvVdJjMqLPtWN5Fq4ULVH_yk0dkBvq8zR8saVMruQ&csui=3)）是硬盘的第一个512字节扇区，包含三个主要部分：主引导程序（446字节），用于加载操作系统；分区表（64字节），记录了硬盘的分区信息；以及一个结束标志（2字节，固定为`55AA`），用于标识扇区的有效性
<!--stackedit_data:
eyJoaXN0b3J5IjpbNDY0MTM3OTgxLC0zNjUzNTYzMjBdfQ==
-->