# Signature to PNG Tool 📝

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![Version: 1.1](https://img.shields.io/badge/Version-1.1-green.svg)
![Bilingual](https://img.shields.io/badge/Language-English%2F中文-brightgreen.svg)

A simple, offline-first tool to convert handwritten signatures to transparent PNG images with adjustable parameters, cropping/rotation, and stroke optimization.

**中文简介：** 一个简洁的离线工具，可将手写签名转换为透明背景的PNG图片，支持参数调节、图像裁剪旋转及笔迹加粗平滑。

## Features ✨

- 📱 **No Installation Required** - Just open the HTML file in your browser
- 🔒 **Completely Offline** - All processing happens locally, images never leave your device
- 🌍 **Bilingual Support** - Switch between Chinese and English
- ✂️ **Image Crop & Rotate** - Interactive crop box and 90° rotation to select your signature area
- 🚀 **High Performance** - Background processing via Web Workers prevents UI lag even with large images
- ✒️ **Stroke Optimization** - Adjust stroke boldness and edge smoothness to make the signature look darker and cleaner
- ⚙️ **Adjustable Parameters** - Threshold and denoise controls for perfect results
- 📊 **Real-time Preview** - See changes instantly as you adjust settings
- 💾 **Easy Download** - PNG files with transparent background

## 特性 ✨

- 📱 **无需安装** - 直接在浏览器打开HTML文件
- 🔒 **完全离线** - 所有处理都在本地进行，图片不上传到任何服务器
- ✂️ **图片裁剪与旋转** - 交互式裁剪框与 90° 旋转，轻松选定签名区域
- 🚀 **高性能处理** - 基于 Web Worker 异步计算，大图调参流畅不卡顿
- ✒️ **笔迹增强控制** - 支持笔迹加粗与边缘平滑，让签名更黑、更圆滑
- 🌍 **双语支持** - 支持中英文切换
- ⚙️ **可调参数** - 阈值和去噪强度可自由调节
- 📊 **实时预览** - 调整参数时实时显示效果
- 💾 **轻松下载** - 生成透明背景的PNG文件

## Quick Start 🚀

### For Windows & macOS Users:
1. Download `signature_tool_bilingual.html`
2. Double-click to open in your browser
3. Upload a signature photo
4. Click **Crop & Rotate** to adjust your image if necessary
5. Adjust parameters (Threshold, Denoise, Boldness, Smoothness) and download PNG

### 快速开始 🚀

### Windows & macOS用户：
1. 下载 `signature_tool_bilingual.html`
2. 双击文件用浏览器打开
3. 上传签名照片
4. 必要时点击 **裁剪与旋转** 调整图片区域
5. 调整参数（阈值、去噪、加粗、平滑）后下载PNG

## How to Use 📖

1. **Upload** - Click upload area or drag & drop a signature image
2. **Crop & Rotate (Optional)** - Cut out unnecessary background and rotate the image 90° if tilted
3. **Preview** - See real-time preview on the right
4. **Adjust**
   - **Threshold**: Lower = keep more details, Higher = keep only black
   - **Denoise**: Removes background texture and shadows
   - **Stroke Boldness**: Expands ink pixels to make the signature bolder and visually darker
   - **Edge Smoothness**: Smooths out jagged edges for a natural look
5. **Download** - Click "Download PNG" button

## 使用方法 📖

1. **上传** - 点击上传区或拖拽签名照片
2. **裁剪与旋转（可选）** - 裁剪掉图片中的多余背景，或将倾斜的照片旋转 90 度
3. **预览** - 右侧实时显示效果
4. **调参**
   - **阈值** - 数值小保留细节，大只保留黑色
   - **去噪** - 消除背景纹理和阴影
   - **笔迹加粗** - 将黑色像素向外膨胀，使签名更黑、更浓
   - **边缘平滑** - 消除硬性二二值化的边缘锯齿，更圆润自然
5. **下载** - 点击"下载PNG"按钮

## Best Practices 💡

- Write signature with black pen on white paper
- Ensure even lighting when taking photo
- Clean background works best
- Start with threshold around 120-180
- Increase denoise if background has texture
- Use "Stroke Boldness" if the pen stroke is too faint or thin
- Use "Edge Smoothness" around 5-10 for anti-aliasing

## 最佳实践 💡

- 用黑色笔在白纸上写签名
- 拍照时光线要均匀
- 背景要尽量干净
- 阈值一般调节在120-180之间
- 如果背景有纹理，增加去噪强度
- 如果笔迹较细或色彩发虚，可以使用“笔迹加粗”功能
- 将“边缘平滑”设在 5-10 之间以获得平滑无锯齿的效果

## Technical Stack

- **Pure HTML/CSS/JavaScript** - No external dependencies
- **Canvas API** - For image processing, cropping, and rotation
- **Gaussian Blur** - Custom denoise implementation
- **Morphological Dilation** - Custom stroke boldness algorithm
- **Soft/Binary Thresholding** - Transition smoothness control
- **Web Workers** - Parallel processing to offload pixel operations and prevent UI lag

## Contributing 🤝

Contributions are welcome! Please feel free to:
- Report bugs
- Suggest features
- Submit pull requests
- Improve documentation

## 贡献 🤝

欢迎贡献！你可以：
- 报告bug
- 建议新功能
- 提交Pull Request
- 改进文档

## License 📄

This project is licensed under the MIT License.

Copyright © 2026 Guiran

## Support 💬

If you have questions or need help:
- Open an issue on GitHub
- Check existing issues for solutions
- Review the documentation


## ⚠️ Legal & Ethical Disclaimer

This tool is provided for **legitimate purposes only**, such as:
- Creating digital signatures for personal use
- Processing signatures for accessibility purposes
- Educational and research purposes

### ❌ Prohibited Uses:
- **Forgery**: Using this tool to forge or create fraudulent signatures
- **Document Fraud**: Falsifying official documents or agreements
- **Impersonation**: Creating signatures to impersonate others
- **Illegal Activities**: Any use that violates local laws or regulations

**Users are solely responsible** for how they use this tool. The developer assumes no liability for misuse.

---

## 法律和道德声明 ⚠️

本工具仅供**合法用途**使用，包括：
- 创建个人数字签名
- 为有需要的人处理签名
- 教育和研究目的

### ❌ 禁止用途：
- **伪造**：使用本工具伪造或创建虚假签名
- **文件欺诈**：篡改官方文件或合同
- **冒充**：创建签名冒充他人
- **违法活动**：任何违反当地法律的使用

**用户完全自行承担**使用本工具的所有责任。开发者对不当使用不承担任何法律责任。
---

⭐ If you find this tool helpful, please give it a star!

⭐ 如果这个工具对你有帮助，请给个Star！
