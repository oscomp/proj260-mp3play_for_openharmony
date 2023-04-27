# proj260-mp3play_for_openharmony
# 在OpenHarmony轻量系统上实现mp3播放

## 项目描述

OpenHarmony作为面向全场景、全连接、全智能时代的基于开源打造的智能终端设备操作系统的框架和平台，在终端设备中中，比如智能家居场景中，我们需要控制设备播放音乐，现在我们需要做的就是能够在OpenHarmony轻量系统上实现mp3播放。

## 源码

- https://gitee.com/openharmony
- https://gitee.com/HiSpark/hi3861_hdu_iot_application
- https://gitee.com/hihope_iot

## 项目导师

- 连志安 [https://gitee.com/lianzhian](https://gitee.com/lianzhian) 
- email [lian_zhian@runkaihong.com.cn](mailto:lian_zhian@runkaihong.com.cn)

## 难度

中等

## 文档

首先我们需要在gitee仓库了解OpenHarmony开源项目https://gitee.com/openharmony，其次我们就可以在结合润和智能家居套件在OpenHarmony轻量系统上实现mp3播放。这里主要利用的就是脉宽调制（Pulse-Width Modulation，PWM）PWM是利用微处理器的数字输出，来对模拟电路进行控制的一种非常有效的技术，通过对一系列脉冲的宽度进行调制，来等效的获得所需要的波形（含形状和幅值），即通过改变导通时间占总时间的比例，也就是占空比，达到调整电压和频率的目的。本项目也主要是利用PWM实现。

## License

Apache 2.0(https://www.apache.org/licenses/LICENSE-2.0.html)

## 预期目标

注意：下面的内容是建议内容，不要求必须全部完成。选择本项目的同学也可与导师联系，提出自己的新想法，如导师认可，可加入预期目标 。

能够利用PWM，调整电压和频率。来实现对不同MP3音乐的播放。

## **选择该赛题的支持**

开发套件支持：提供给参赛队伍开发套件，此开发板采用海思Hi3861芯片，它集成了 32位高能效的 RISC-V 指令集架构的 CPU，内置了 SRAM 和 Flash，可以独立运行程序，它的外设接口也比较丰富，包括：15个通用输入/输出（General Purpose Input/Output，GPIO）接口；支持7路模数转换器（Analog to Digital Converter，ADC）输入；支持6路脉宽调制（Pulse Width Modulation，PWM）输出；支持3个通用异步收发器（Universal Asynchronous Receiver & Transmitter，UART）接口；支持2个串行外设接口（Synchronous Peripheral Interface，SPI）；集成了两个内部集成电路（The Inter Integrated Circuit，I2C）接口；另外，它还具备一个内部集成电路音频（Inter-IC Sound，I2S）接口和一个安全数字输入输出（Secure Digital Input/Output，SDIO）从机接口。


技术答疑指导：针对OpenHarmony操作系统及本赛题技术要点，资深研发工程师提供专业的技术支持、指导，全程辅导技术方案的实现。

技术资料：提供相关技术资料和对应索引，指导赛题方向。
