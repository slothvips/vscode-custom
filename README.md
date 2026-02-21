# VSCode 资源管理器字体大小自定义样式

为 VSCode 资源管理器（文件树）自定义字体大小的 CSS 样式文件。

## 使用方法

### 1. 安装扩展

在 VSCode 扩展市场搜索并安装 **Custom CSS and JS Loader**（作者：iahu）。

### 2. 添加自定义 CSS

1. 打开命令面板：`Cmd + Shift + P`（Mac）或 `Ctrl + Shift + P`（Windows）
2. 输入 `Custom CSS` 选择 "Preferences: Open Custom CSS and JS"
3. 将本仓库的 `vscode-explorer-font-size.css` 内容复制到打开的文件中

### 3. 启用

1. 同样打开命令面板
2. 输入 `Reload Custom CSS` 选择 "Developer: Reload Custom CSS"
3. 或者直接重启 VSCode

## 自定义字体大小

如需调整字体大小，修改 CSS 文件中的 `font-size: 16px` 为你想要的数值即可。

## 卸载

如果不再需要，卸载扩展前记得运行 `Clean Cache` 清理注入的 CSS。
