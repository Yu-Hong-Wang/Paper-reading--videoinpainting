# 《AVID: Any-Length Video Inpainting with Diffusion Model》

## 研究背景
视频修复目前存在以下问题：时间一致性（物体在时间域上是连贯的）；不同类型修复任务（替换物体，修改颜色纹路，视频延长等所需要的结构保真度不同）；视频长度要求（需要尽可能地能够处理更长的视频）。

## 解决方法--AVID框架
### 运动模块（Motion Modules）
目的：确保时间一致性。

### 结构引导模块（Structure Guidance Module）
目的：针对不同修复任务。

### 零样本推理管道（Zero-shot Inference Pipeline）
目的：处理任意长度的视频。
由时间多扩散采样（Temporal MultiDiffusion Sampling）和中帧注意力引导机制（Middle-frame Attention Guidance）组成。

## 待解决的问题
