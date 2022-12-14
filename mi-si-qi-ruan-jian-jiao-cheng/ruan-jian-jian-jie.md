# 软件简介

&#x20;   Mixly（米思齐）是一款图形化编程软件。用户可以通过拼接积木块的方式来编写程序。目前为止，Mixly已经支持Arduino，micropython，python等编程语言。

### 特点

#### 易用性

当前多数中小学机房安装了硬盘保护卡，频繁的软件安装与更新工作，给机房的管理工作造成极大的不便。为此，Mixly在设计上做到了完全绿色使用。用户直接从网上下载Mixly软件包，解压后即可在Windows XP及以上的操作系统运行。软件无需额外安装浏览器，也不用安装Java运行环境，极大方便了师生的使用。

#### 简单性

Mixly采用了Blockly图形化编程引擎，使用图形化的积木块代替了复杂的文本操作，为学生的快速入门奠定了良好的基础。另外，Mixly的开发团队使用以下方式来帮助师生快速熟悉软件：第一，用不同颜色的示意图标代表不同类型的功能块，方便用户归类区分；第二，在复合功能块中提供默认选项，有效减少用户的拖动次数；第三，在同一个界面整合软件的所有功能；第四，提供参考教程及代码示例。

#### 功能性

当前，很多学校将组织或参与创客类比赛作为创客教育的一种途径，比赛的竞技性对软件的功能提出了更高的要求。因此，Mixly在功能的设计上力求和Arduino IDE的文本编程保持一致，目前最新发布的Mixly 0.97版已经实现Arduino的所有官方功能（包括中断处理），并加入了大量的第三方扩展库功能，如红外遥控、超声波等，可以保证课程开设和各类创客比赛的双重需求。

#### 普适性

Mixly在设计上考虑了绝对的普适性。首先，对于Arduino官方支持的所有开发板，Mixly都提供了完美的支持：Mixly会根据开发板的类型自动改变模块中的管脚号、中断号、模拟输出管脚等；其次，对于Arduino支持的第三方开发板，Mixly同样支持，用户只要把相应开发板的定义复制到Mixly中即可。如国内大量的ESP8266开发板、各类用户修改后的开发板等等，以保证用户在开发板选择上的最大自由度。

#### 延续性

图形化编程系统的目标绝对不是替换原有的文本编程方式，而是希望学生通过图形化编程更好更快地理解编程的原理和程序的思维，并为未来的文本编程打好基础。Mixly的设计理念也是如此。在软件的设计上加入了更多的可延续性内容，从而保护用户的学习成果。具体来说，包括引入变量类型、在模块的设计上尽量保持和文本编程的一致、支持图形编程和文本编程的对照等。

#### 生态性

生态性是Mixly最重要的设计理念，也是它区别于其它Arduino图形化编程的最重要特征。为了实现Mixly可持续发展，Mixly在设计上既允许厂商开发自己的特有模块（当前已经支持DfRobot、StartLab、MakeBlock、Sense、Seeed、Lubot，Microduino、Ruilong、NodeMcu，Nova，用户需要有JavaScript编程基础才能制作这部分模块），也允许用户直接利用Mixly的图形化编程功能生成通用模块（如数码管显示、蜂鸣音播报等，用户只需会使用Mixly即可制作这部分模块）。以上两类模块均可通过“导入库”功能导入Mixly系统，从而在Mixly软件的普及中实现用户自身的价值。
