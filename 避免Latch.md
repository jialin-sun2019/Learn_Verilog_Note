# 触发器和锁存器

##### 锁存器(Latch)

##### latch    ---是电平触发的存储单元

1、基本RS触发器(电平触发)

![4](image\4.JPG)

2、同步RS触发器

![5](image\5.JPG)

3、D触发器

![6](image\6.JPG)

##### 触发器---是边缘触发的储存单元



寄存器(register) --- 寄存器可以综合成触发器，也可以综合为锁存器，希望综合为：触发器

1、边缘触发

![7](image\7.jpg)

2、脉冲触发

![8](image\8.jpg)



#### 避免Latch(锁存器)

1、完整的if - else 结构

2、完整的case - default 结构

3、原信号 给 自己赋值  ex:  signal_a = signal_a;

4、always@(signal)  敏感信号不完整；