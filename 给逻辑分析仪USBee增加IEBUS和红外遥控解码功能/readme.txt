将“CustomUSBeeSuiteDecoder.dll”动态库拷贝复制到USBee安装目录下即可，默认为“C:\Program Files\CWAV Inc\USBee Suite”。

使用：连接AX-Pro逻辑分析仪，打开USBee Suite软件，单击任意通道弹出“Channel Settings”对话框，然后点击“Custom”选项，在出现的对话框中，输入“IEBUS x”，
x代表逻辑分析仪通道号，从0到7（有些逻辑分析仪支持16通道则从0到15）最后点击“Save”即可。

--友情提示，有些AX-Pro逻辑分析仪丝印标注的通道号是从1到8，而USBee Suite软件则是从0到7排序，所以AX-Pro的通道号是比SBee Suite软件的通道号多1的。
例如，AX-Pro分析仪选择通道3，而实际SBee Suite软件分析得到的数据会在通道2处显示。

--意外惊喜，在“Custom”对话框中，试一下输入“NECIR x”(x:0~7)。是的，除了可以分析IEBUS外，还可以支持红外遥控分析功能哦。
其实这些额外功能可以由客户自己添加，在“C:\Program Files\CWAV Inc\USBee Suite\CustomUSBeeSuiteDecoder”有一个项目，用VB 2008以上版本打开，
自己按照项目里提供的历程编写解码函数。由于该项目是USBee Suite软件原始的版本，所以里面是不含IEBUS功能的哦，
需要IEBUS功能代码或有任何意见者可发送邮件到：fjm2635658@qq.com。

                                                                        Jimmyfong
                                                                        20120908
