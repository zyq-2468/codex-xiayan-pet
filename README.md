# 夏彦 Codex 桌宠

Codex 自定义桌宠，让夏彦陪你一起工作 ✨

本仓库提供桌宠配置和动画图集，使用前需要安装支持自定义桌宠的 Codex 桌面客户端。

## 文件结构

```text
codex-xiayan-pet/
├── README.md
└── xia-yan/
    ├── pet.json          # 桌宠配置
    └── spritesheet.webp  # 动画图集
```

## 安装方法（Windows）

1. 点击仓库页面的 **Code → Download ZIP**，下载并解压。
2. 按 `Win + R`，输入 `%USERPROFILE%\.codex`，按回车打开。
3. 如果没有 `pets` 文件夹，新建一个。
4. 将下载内容中的整个 `xia-yan` 文件夹复制到 `pets` 文件夹内。

安装后的目录应为：

```text
%USERPROFILE%\.codex\pets\xia-yan\
├── pet.json
└── spritesheet.webp
```

5. 打开 Codex，在桌宠选择界面中找到「夏彦」并选择。如果没有显示，尝试退出并重新打开 Codex。

## 效果演示

https://github.com/user-attachments/assets/0623b5f6-c897-4890-a7c3-a92916842977

## 常见问题

### 为什么找不到相关文件？

请确认：

- 使用的是支持自定义桌宠的 Codex 桌面客户端。
- `pet.json` 和 `spritesheet.webp` 都放在 `xia-yan` 文件夹内。
- 没有多套一层目录，例如 `pets\xia-yan\xia-yan\`。

### 可以单独运行吗？

这是供 Codex 加载的桌宠素材包，需要配合 Codex 桌面客户端使用。

## 反馈

遇到问题或有建议，欢迎在本仓库提交 Issue。
