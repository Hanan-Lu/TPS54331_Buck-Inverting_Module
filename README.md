# 简介

> 本项目是一个基于TPS54331的DC-DC转换器，通过修改一颗电阻的安装位置，可以配置为正压输出或负压输出。
> 
> 本项目初始设计参数为输出5V/1A或-5V/500mA，如有其它参数需求用户可自行计算电感及补偿网络器件参数。

# 使用

![实物图]<[raw.githubusercontent.com](https://raw.githubusercontent.com/Hanan-Lu/TPS54331_Buck-Inverting_Module/main/PCB/TPS54331%20PCBA.jpg)

> 如图，上面模块配置为正压输出(安装R8，不安装R7)，即普通的Buck模式；
> 
> 下面的模块配置为反相输出(安装R7，不安装R8)，即Inventor-Buck模式；
> 
> ***<font color=red>注意，反相输出时最大输入电压=28V-输出电压绝对值</font>***

# 原理

> 原理请参见Document目录下的"*Using a buck converter in an inverting.pdf*",本处不在赘述。


