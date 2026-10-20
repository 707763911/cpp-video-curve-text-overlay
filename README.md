# C++ Video Curve Text Overlay

C++ 视频帧上叠加数据曲线与文字的通用工程实现。仓库内素材与数据为脱敏合成数据，不包含客户视频或业务数据。

## 功能
- 视频/帧序列读取
- 数据曲线绘制与坐标映射
- 文字渲染与位置配置
- 时间戳同步
- 通过 FFmpeg 输出合成视频

## 技术栈
C++17、OpenCV、FFmpeg、CMake

## 快速开始
```bash
cmake -S . -B build
cmake --build build
# 传入输入视频、曲线 CSV、输出路径
