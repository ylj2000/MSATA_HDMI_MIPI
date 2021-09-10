# HDMI转MIPI屏幕驱动

>这是一个可以将HDMI信号转换位MIPI信号，驱动MIPI屏幕的模块。基于东芝TC358870方案。

>适合二次开发，如果只是想做一个能直接用的，建议直接做https://github.com/ylj2000/HDMI_To_MIPI 中的成品。

# 关于硬件和软件

>核心板采用MSATA接口引出HDMI和MIPI接口，以及控制底板上部分电路所需的单片机IO口，同时包含音频电路，可以输出电脑音频。主芯片为TC358870以及STM32芯片，目前可以选择STM32F401CBU6/STM32F401CCU6/STM32F071CBU6,在现在这个MCU涨飞的时候，401可以8-9元，071可以4元左右在咸鱼淘到，算是比较便宜的方案了。核心板上，如果采用STM32F071，则单片机的晶振电路可以不焊。

# 更新说明
>2021.09.10 ：核心板的原理图和PCB，LQ055T3SX02Z的底板，071和401程序。底板上用排针引出了音频信号，可以另外加功放或者接耳机。程序支持热插拔HDMI、电脑休眠等。

# 注意
> 本项目不支持任何形式的私自产品化，仅允许个人DIY使用。
