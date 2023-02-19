# Traffic_light_simulation_with_8086_proteus

**课程设计任务书**

**1.**    **设计目的：**

  通过课程设计，综合《微机原理与应用》的课程知识，将其运用到具体的实际应用中，从而达到融合贯通。

**2.**    **设计内容：**

  利用EDA工程软件Proteus，仿真设计一个人行过街信号灯控制系统。系统由两组“信号灯组（红、绿、黄）+两位倒计时牌”指挥双向车流，由两组“信号灯组（红、绿）+过街信号灯按钮”指挥行人过街。

**3.**    **功能要求：**

当无行人过街需求时，信号灯组（红、绿、黄）长显示“绿”，倒计时牌不工作，信号灯组（红、绿）显示“红”；

当有行人需要过过街时，手动按下“过街信号灯按钮”，倒计时牌开始显示绿色倒计时35秒，当倒计时归“0”时，信号灯组（红、绿、黄）显示“红”，同时倒计时牌开始显示红色倒计时20秒，信号灯组（红、绿）显示“绿”，行人可以过街；

当红色当倒计时归“0”时，倒计时牌停止工作，信号灯组（红、绿、黄）显示“绿”，信号灯组（红、绿）显示“红”，行人禁止过街。

**4.**    **报告要求：**

(1)  课程设计提交以实验报告形式，格式要求参照科学论文要求；

(2)  报告框架要求有“封面”“目录”“具体章节”“参考资料”等；

(3)  “具体章节”主要要求有：

①   计算机五大组成部份的元器件选择；

②   控制系统的全局电路图、关键部份（CPU、接口）的局部电路图；

③   接口设计的详细具体说明，比如端口地址等；

④   接口芯片的初始化程序（要求汇编语言）及其文字说明；

⑤   有关信号周期控制的编程，这部份仅做参考，不属于考核内容。
