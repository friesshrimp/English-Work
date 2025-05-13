# 一方云剪

一方云剪是一款不依赖服务器服务的视频剪辑站点，通过整合@hughfenghen作者的WebAV、opfs-tools，添加一些必要的剪辑功能，希望能给相关开发者更多的帮助和启发。如果对您有帮助，请给个star支持一下。如果在使用中遇到问题，请在issue中提出，也欢迎提交PR。

## 项目地址

[https://github.com/caohongz/yifang-clip](https://github.com/caohongz/yifang-clip)

## 项目预览

[https://caohongz.github.io/yifang-clip/](https://caohongz.github.io/yifang-clip/)

## 功能特点

1. 多轨道编辑
   - 支持多个视频、音频、图片和文字轨道
   - 轨道间支持拖拽排序和位置调整
   - 轨道操作历史记录
   - 最多支持10个并行轨道

2. Media Editing Functions
    - Video Segmentation
    - Visualization of Audio Waveform
    - Precise Positioning at the Video Frame Level
    - Support for Dynamic Images (GIF)
    - Support for Volume Adjustment of Video Clips
    - Support for Filters of Video Clips 

3. 文字编辑功能
   - 丰富的文字样式设置
   - 自定义字体大小、颜色
   - 文字阴影和描边效果
   - 多种文本对齐方式

4. 实时预览
   - 实时预览编辑效果
   - 支持全屏预览
   - 帧进帧退精确预览
   - 自适应画布尺寸

5. 项目管理
   - 本地项目保存

6. 导出功能
   - 支持导出MP4格式
   - 导出进度实时显示
   - 支持中断导出操作

7. 本地化存储
   - 使用IndexedDB存储项目数据
   - 使用OPFS存储媒体文件
   - 无需服务器即可运行
   - 保护用户隐私数据

8. 用户界面
   - 现代化深色主题界面
   - 响应式布局设计
   - 可调节编辑区域比例
   - 友好的拖放操作体验

## 注意事项

1. 浏览器兼容性
   - 仅支持本地部署或HTTPS协议
   - 仅支持 Chrome 102+和 Edge 102+版本
   - 建议使用最新版 Chrome或 Edge 以获得最佳体验

2. 存储限制
   - 使用 IndexedDB 存储项目数据
   - 使用 OPFS (Origin Private File System) 存储媒体文件
   - 注意浏览器存储空间限制

3. 性能考虑
   - 建议处理 1080p 以下视频
   - 长视频处理可能需要较长时间
   - 导出时占用资源较多,请耐心等待

## 技术栈

- Vue 3
- TypeScript
- Element Plus
- WebCodecs API
- WebAV
- PIXI.js (v7.4.2)
- IndexedDB
- Tailwind CSS

## 贡献指南

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 提交 Pull Request

## 致谢

- [@hughfenghen/WebAV](https://github.com/bilibili/WebAV)
- [@hughfenghen/opfs-tools](https://github.com/hughfenghen/opfs-tools)

## License

MIT License - 详见 [LICENSE](LICENSE) 文件

