# Fcitx5 粉白蓝主题 (Pink White Blue)

一个给 [Fcitx5](https://fcitx-im.org/) 的中文输入法皮肤：**白底 + 蓝色边框 + 粉色候选高亮**。

## 预览配色

| 部分 | 颜色 |
|---|---|
| 背景 | `#ffffff`（白） |
| 边框 | `#6f9dff`（蓝） |
| 候选高亮 | `#f472b6`（粉） |
| 普通文字 | `#30384a` |
| 高亮文字 | `#ffffff` |

## 安装

```bash
mkdir -p ~/.local/share/fcitx5/themes
git clone https://github.com/<你的用户名>/fcitx5-pink-white-blue-theme.git
cp -r fcitx5-pink-white-blue-theme ~/.local/share/fcitx5/themes/pink-white-blue
```

## 启用

- 图形界面：`fcitx5-configtool` → 外观 → 主题 → 选「粉白蓝」；
- 或命令行：

```bash
printf 'Theme=pink-white-blue\n' > ~/.config/fcitx5/conf/classicui.conf
fcitx5 -r
```

## 自定义

编辑 `theme.conf`，改 `BorderColor`（边框色）、`BorderWidth`（边框宽）、`[InputPanel/Highlight]` 的 `Color`（高亮色）等，然后 `fcitx5 -r` 重载。

## License

[MIT](LICENSE)
