# Calibration pattern generator for ipad

当你使用电子屏幕作为视觉系统标定板时，不妨试试使用本项目来生成标定图案。仅依赖电子屏幕的尺寸和对角线长度等基础参数，就可以生成用于高精度立体视觉系统标定的标定板图案。

* 本项目会生成于电子屏幕等分辨率的图像，根据由屏幕对角线长度换算标记点实际物理间距
* 提供实心原点（PMLAB和千眼狼DIC软件支持的标定板图案）和编码圆环（[OpenCorr](www.opencorr.org)）等两种图案生成功能
* 可自由调节图案在画面中的位置，适应实际实验场景的需求
<img width="1785" height="1322" alt="image-20251114120915735" src="https://github.com/user-attachments/assets/c178ff8e-7508-466a-93ef-ce0b0a66d651" />

