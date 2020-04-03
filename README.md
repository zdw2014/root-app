## 说明
- 这个代码库演示了安装一个App，然后静默安装其他应用。

## 原理
- 因为运行在root设备，可以直接使用shell命令，所以基本上可以为所欲为。

## 项目结构
整个项目分成了两个module
- 一个是需要静默安装的第三方App
- 一个是主App负责安装第三方App
- 为了直观感受安装过程，demo做了分步处理

## 使用场景
- 适合自己的设备进行一些非常规开发工作
1. 比如大屏Android设备
2. 嵌入式设备
3. 自定义Android设备
