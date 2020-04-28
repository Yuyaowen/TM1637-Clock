# TM1637时钟显示
shell脚本编写，无内核驱动
## 使用方法
> 定义信号引脚，修改
> ```
> # Define pins:
> clk_pin_num=199
> dio_pin_num=198
> ```
> 其中的引脚编号为Linux中GPIO子系统的编号，用于export操作
> 电源可以使用5V或者3.3V
## 图片
![](1.jpg)
![](2.jpg)