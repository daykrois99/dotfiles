
# dotfiles 目录结构与说明

本仓库收录了适用于 Linux（Wayland 环境，主力 Hyprland）的常用配置文件，助你快速搭建美观高效的桌面环境。

## 目录结构

```
.
├── fontconfig/           # 字体渲染与优先级配置
│   └── fonts.conf
├── hypr/                 # Hyprland 相关配置
│   ├── hyprland.conf     # Hyprland 主配置
│   ├── hyprpaper.conf    # 壁纸管理器 hyprpaper 配置
│   └── wallpaper/        # 壁纸文件夹
│       └── goku.jpeg
├── Pictures/             # 截图等图片资源
│   └── screen.png
├── waybar/               # Waybar 状态栏配置
│   ├── config.jsonc
│   └── style.css
└── yazi/                 # Yazi 终端文件管理器配置
    └── yazi.toml
```

---

## 详细说明

### fontconfig/
- **fonts.conf**：
  - 用于自定义系统字体渲染、字体优先级，适配中英文混排、编程字体等场景。
  - 推荐字体：CaskaydiaMono Nerd Font、FiraCode Nerd Font、Noto Sans/Serif CJK SC。

### hypr/
- **hyprland.conf**：
  - Hyprland 窗口管理器主配置，包含环境变量、快捷键、显示器、窗口行为等设置。
  - 示例：集成截图（grim+slurp）、Waybar、Hyprpaper 启动等。
- **hyprpaper.conf**：
  - Hyprland 官方壁纸管理器配置，支持多屏壁纸。
  - 示例：预加载并设置 goku.jpeg 为壁纸。
- **wallpaper/**：
  - 存放壁纸图片。

### Pictures/
- **screen.png**：
  - 示例桌面截图或常用图片资源。

### waybar/
- **config.jsonc**：
  - Waybar 状态栏的主配置，支持模块化、JSONC 格式（可注释）。
  - 包含音量、时钟、CPU、内存、温度、托盘等模块。
- **style.css**：
  - Waybar 的样式表，支持自定义配色、圆角、字体等。
  - 推荐 Nerd Font 字体获得更好图标支持。

### yazi/
- **yazi.toml**：
  - Yazi 终端文件管理器主配置。
  - 示例：显示隐藏文件。


---

## 截图预览

![桌面截图](./Pictures/screen.png)
