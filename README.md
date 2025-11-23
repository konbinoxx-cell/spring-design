# Compression Spring Designer | 压缩弹簧设计计算器

A comprehensive web-based tool for designing and calculating compression springs with technical drawings and real-time validation.

一个功能完整的网页版压缩弹簧设计计算工具，包含技术图纸和实时验证功能。

🔗 **[Live Demo / 在线演示](https://konbinoxx-cell.github.io/compression-spring-designer/)**

⭐ **Star this repo if you find it useful!** | **如果觉得有用请给个星标！**

---

## 🌟 Features | 功能特点

### English
- **Complete Spring Design Calculations**: Automatically calculates all critical parameters including mean diameter, spring rate, number of coils, pitch, and stress analysis
- **Technical Drawing Generation**: Interactive SVG-based technical drawings with dimension annotations
- **Material Database**: Pre-configured material properties for common spring materials (Carbon Spring Steel, Piano Wire, Stainless Steel)
- **Design Validation**: Real-time validation of spring index, safety factor, and stability
- **Bilingual Support**: Available in both English and Chinese versions
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Export-Ready**: Clean, professional output suitable for manufacturing documentation

### 中文
- **完整的弹簧设计计算**：自动计算所有关键参数，包括中径、弹簧刚度、圈数、节距和应力分析
- **技术图纸生成**：基于 SVG 的交互式技术图纸，带有尺寸标注
- **材料数据库**：预配置常用弹簧材料的性能参数（碳素弹簧钢丝、钢琴钢丝、不锈钢丝）
- **设计验证**：实时验证旋绕比、安全系数和稳定性
- **双语支持**：提供英文和中文两个版本
- **响应式设计**：在桌面和移动设备上均可完美运行
- **可导出**：整洁专业的输出，适合制造文档

---

## 📋 Calculated Parameters | 计算参数

### English
The tool calculates the following parameters:
- Mean Diameter (D)
- Spring Rate (k)
- Effective Coils (n)
- Total Coils (n₁)
- Pitch (t)
- Solid Length (H₃)
- Spring Index (C)
- Maximum Shear Stress (τ)
- Safety Factor
- Maximum Working Length
- Solid Load
- Stability Status

### 中文
工具计算以下参数：
- 中径 (D)
- 弹簧刚度 (k)
- 有效圈数 (n)
- 总圈数 (n₁)
- 节距 (t)
- 压并长度 (H₃)
- 旋绕比 (C)
- 最大切应力 (τ)
- 安全系数
- 最大工作长度
- 压并载荷
- 稳定性状态

---

## 🚀 Usage | 使用方法

### English

1. **Download the HTML file**
   - Choose your preferred language version:
     - `en/compression-spring-designer.html` (English)
     - `cn/compression-spring-designer.html` (Chinese)
   - Or simply open `index.html` to select your language

2. **Open in browser**
   - Simply double-click the HTML file
   - No installation or server required
   - Works offline

3. **Input parameters**
   - Enter maximum and minimum working loads (N)
   - Specify working stroke (mm)
   - Set outer diameter constraint (mm)
   - Define free length (mm)
   - Input wire diameter (mm)
   - Select material type

4. **Calculate**
   - Click "Calculate Design" button
   - Review results and technical drawing
   - Adjust parameters as needed based on recommendations

5. **Export/Print**
   - Use browser's print function (Ctrl/Cmd + P)
   - Save as PDF for documentation
   - Take screenshots of the technical drawing

### 中文

1. **下载 HTML 文件**
   - 选择您偏好的语言版本：
     - `en/compression-spring-designer.html`（英文）
     - `cn/compression-spring-designer.html`（中文）
   - 或直接打开 `index.html` 选择语言

2. **在浏览器中打开**
   - 直接双击 HTML 文件
   - 无需安装或服务器
   - 支持离线使用

3. **输入参数**
   - 输入最大和最小工作载荷 (N)
   - 指定工作行程 (mm)
   - 设置外径限制 (mm)
   - 定义自由长度 (mm)
   - 输入线径 (mm)
   - 选择材料类型

4. **计算**
   - 点击"计算设计结果"按钮
   - 查看结果和技术图纸
   - 根据建议调整参数

5. **导出/打印**
   - 使用浏览器打印功能（Ctrl/Cmd + P）
   - 保存为 PDF 用于文档
   - 截屏技术图纸

---

## 📐 Design Formulas | 设计公式

### English

**Spring Rate:**
```
k = (F₂ - F₁) / h
```

**Effective Coils:**
```
n = Gd⁴ / (8D³k)
```

**Shear Stress:**
```
τ = K × 8FD / (πd³)
```

**Spring Index:**
```
C = D / d
```

**Wahl Correction Factor:**
```
K = (4C - 1) / (4C - 4) + 0.615 / C
```

### 中文

**弹簧刚度：**
```
k = (F₂ - F₁) / h
```

**有效圈数：**
```
n = Gd⁴ / (8D³k)
```

**切应力：**
```
τ = K × 8FD / (πd³)
```

**旋绕比：**
```
C = D / d
```

**Wahl 曲度系数：**
```
K = (4C - 1) / (4C - 4) + 0.615 / C
```

---

## 📊 Material Properties | 材料性能

### English

| Material | Shear Modulus (MPa) | Allowable Stress (MPa) | Young's Modulus (MPa) |
|----------|---------------------|------------------------|----------------------|
| Carbon Spring Steel (SWC) | 78,500 | 800 | 206,000 |
| Piano Wire (SWP) | 78,500 | 900 | 206,000 |
| Stainless Steel (SUS304) | 69,000 | 600 | 193,000 |

### 中文

| 材料 | 剪切模量 (MPa) | 许用应力 (MPa) | 弹性模量 (MPa) |
|------|---------------|---------------|---------------|
| 碳素弹簧钢丝 (SWC) | 78,500 | 800 | 206,000 |
| 钢琴钢丝 (SWP) | 78,500 | 900 | 206,000 |
| 不锈钢丝 (SUS304) | 69,000 | 600 | 193,000 |

---

## ⚙️ Design Guidelines | 设计指南

### English

**Recommended Ranges:**
- Spring Index (C): 4 - 16
- Safety Factor: > 1.2
- Slenderness Ratio: < 2.6 (for stability without guiding)
- Solid Load: < 1.25 × Maximum Working Load

**Design Validation:**
- ✅ Green indicator: Design is valid and ready for manufacturing
- ⚠️ Yellow indicator: Parameters need adjustment, check recommendations

### 中文

**推荐范围：**
- 旋绕比 (C)：4 - 16
- 安全系数：> 1.2
- 细长比：< 2.6（无导向时保持稳定）
- 压并载荷：< 1.25 × 最大工作载荷

**设计验证：**
- ✅ 绿色指示器：设计合理，可以进行制造
- ⚠️ 黄色指示器：需要调整参数，查看建议

---

## 🛠️ Technical Requirements | 技术要求

### English
- Modern web browser (Chrome, Firefox, Safari, Edge)
- JavaScript enabled
- No internet connection required (standalone HTML file)
- Recommended screen resolution: 1024×768 or higher

### 中文
- 现代网页浏览器（Chrome、Firefox、Safari、Edge）
- 启用 JavaScript
- 无需互联网连接（独立 HTML 文件）
- 推荐屏幕分辨率：1024×768 或更高

---

## 📁 File Structure | 文件结构

```
compression-spring-designer/
├── index.html                                 # Language selection page
├── en/
│   └── compression-spring-designer.html       # English version
├── cn/
│   └── compression-spring-designer.html       # Chinese version
└── README.md                                  # This file
```

---

## 🌟 Support This Project | 支持项目

### English
If you find this tool helpful, please consider:
- ⭐ Star this repository
- 🍴 Fork it for your own projects
- 🐛 Report issues
- 💡 Submit pull requests

### 中文
如果这个工具对您有帮助，欢迎：
- ⭐ 给项目加星标
- 🍴 Fork 项目进行二次开发
- 🐛 提交 Issue 报告问题
- 💡 提交 Pull Request 贡献代码

---

## 🤝 Contributing | 贡献

### English
Contributions are welcome! Please feel free to submit issues or pull requests for:
- Bug fixes
- New features
- Material database expansion
- Translation improvements
- Documentation enhancements

### 中文
欢迎贡献！请随时提交问题或拉取请求，包括：
- 错误修复
- 新功能
- 材料数据库扩展
- 翻译改进
- 文档增强

---

## 📄 License | 许可证

### English
This project is open source and available under the MIT License.

### 中文
本项目为开源项目，采用 MIT 许可证。

---

## 📧 Contact | 联系方式

### English
For questions, suggestions, or issues, please open an issue in the repository.

### 中文
如有疑问、建议或问题，请在仓库中提交 issue。

---

## 🙏 Acknowledgments | 致谢

### English
- Built with React and Tailwind CSS
- Uses Lucide React for icons
- Based on standard mechanical engineering principles and formulas

### 中文
- 使用 React 和 Tailwind CSS 构建
- 使用 Lucide React 图标库
- 基于标准机械工程原理和公式

---

**Version | 版本**: 1.0.0  
**Last Updated | 最后更新**: 2024

---

## 🌐 Screenshots | 屏幕截图

### English Version | 英文版
![Input Interface](screenshot-input-en.png)
![Technical Drawing](screenshot-drawing-en.png)
![Results Display](screenshot-results-en.png)

### Chinese Version | 中文版
![输入界面](screenshot-input-zh.png)
![技术图纸](screenshot-drawing-zh.png)
![结果显示](screenshot-results-zh.png)

---

**Made with ❤️ for Engineers | 为工程师用心打造 ❤️**
