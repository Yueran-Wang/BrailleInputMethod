# Braille Keyboard

**Braille Keyboard** 是一个为macOS设计的盲文输入法，旨在帮助视障用户更有效地使用电脑进行通讯和日常工作。它支持多种盲文标准，提供直观的用户界面和可高度自定义的使用体验。

## 功能特点

- **支持多种盲文标准**：包括标准盲文和计算机盲文。
- **用户友好的交互界面**：专为盲文键盘优化，易于导航和使用。
- **高度可配置**：允许用户自定义键盘设置，如盲文规则、响应速度等。
- **多语言支持**：支持英语和中文输入，未来将支持更多语言。

## 安装指南

要安装**Braille Keyboard**，请按照以下步骤操作：

1. 确保您的系统满足最小需求（macOS 10.15 或更高版本）。
2. 从GitHub仓库克隆源代码：
   ```bash
   git clone https://github.com/yourusername/braille_keyboard.git
   ```
3. 进入项目目录并安装必要的依赖：
   ```bash
   cd braille_keyboard
   pip install -r requirements.txt
   ```
4. 运行安装脚本：
   ```bash
   python setup.py install
   ```

## 使用方法

启动**Braille Keyboard** 输入法：

```bash
python braille_keyboard/main.py
```

按照屏幕上的指示进行操作。您可以通过配置文件`config.py`自定义键盘设置。

## 如何贡献

我们欢迎所有对改进盲文键盘输入法感兴趣的开发者和用户贡献自己的力量。您可以通过以下方式参与：

- **提交Bug报告**：如果您发现任何问题，请通过GitHub Issues提交。
- **提出功能请求**：有好的想法？通过Issues告诉我们。
- **提交拉取请求**：对代码进行改进，并提交PR。

详细的贡献指南请查看`CONTRIBUTING.md`文件。

## 许可证

本项目采用 [MIT 许可证](LICENSE)。详细信息请查阅随附的`LICENSE`文件。

## 联系方式

如有任何问题或建议，请通过 [your.email@example.com](mailto:your.email@example.com) 联系我们。