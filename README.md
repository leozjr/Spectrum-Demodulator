# 时间调制型傅里叶变换干涉光谱仪

> 本项目为自主研发的时间调制型傅里叶变换干涉光谱仪的配套软件

## 原理

干涉成像光谱技术是一种通过干涉成像系统同时获得被测对象空间信息和光谱信息的成像技术。 它利用干涉图和复原光谱之间的傅立叶变换关系，通过对干涉图进行傅里叶积分变换计算得到被测对象的光谱信息 。

主要步骤有：

- 光信号分割：将待测光信号和参考光信号分别分割成两个光路径。

- 时间调制：通过在一个光路径中引入可调节的时间延迟，使得待测光信号和参考光信号在时间上产生相对运动。

- 干涉：将待测光信号和参考光信号合并在一起，使它们发生干涉现象。干涉产生的强度变化将包含待测光信号的频谱信息。

- 信号检测：利用光敏探测器或者其他类型的探测器，测量干涉信号的强度变化。

- 傅里叶变换：对检测到的干涉信号进行傅里叶变换，将时域的信号转换为频域的信号。

- 光谱重建：通过对得到的频谱信息进行处理和解释，可以还原出待测光信号的频谱特征，从而实现光谱分析。

## 软件功能

 - 定义自定义任务，拍摄时间调制图像序列
 - 基于傅里叶变换从干涉数据立方体重构光谱数据
 - 对光谱数据立方体进行RGB和灰度通道的增强展示
 - 查看像素点光谱曲线
 - 对选定颜色进行颜色分割及光谱分割
 - 显示Top N% 的最大值点

后续功能仍在开发中……

![](https://github.com/leozjr/Spectrum-Demodulator/blob/main/Docs/解调结果.png)

![](https://github.com/leozjr/Spectrum-Demodulator/blob/main/Docs/灰度界面.png)

![](https://github.com/leozjr/Spectrum-Demodulator/blob/main/Docs/颜色选择.png)

![](https://github.com/leozjr/Spectrum-Demodulator/blob/main/Docs/最大值.png)

![](https://github.com/leozjr/Spectrum-Demodulator/blob/main/Docs/相机驱动.png)

