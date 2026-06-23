
# 符

## VS Code Git 操作指南

### 1. 打开 Source Control 面板

点击 VS Code 左侧活动栏的第三个图标（分支图标 🌿），或使用快捷键：
- **macOS**: `Ctrl + Shift + G`
- **Windows/Linux**: `Ctrl + Shift + G`

### 2. Source Control 面板说明

打开后你会看到：
- **源代码管理提供程序**: 显示 Git 状态
- **更改**: 显示未暂存的文件
- **暂存的更改**: 显示已暂存的文件
- **提交消息框**: 输入 commit 信息
- **提交按钮**: `✓` 提交更改

### 3. 常用 Git 操作

| 操作 | 步骤 |
|------|------|
| 暂存文件 | 点击文件旁的 `+` 号 |
| 暂存所有更改 | 点击 "更改" 旁的 `+` 号 |
| 提交 | 输入消息，按 `Ctrl + Enter` |
| 推送到远程 | 点击底部状态栏的分支名，选择 "推送" |
| 拉取更新 | 点击底部状态栏的同步图标 |

### 4. 当前仓库状态

- **远程仓库**: `git@github.com:Fjord-147/-.git`
- **当前分支**: `main`
- **提交记录**: 2 commits
- **已推送**: ✅ 是

### 5. 添加远程仓库（VS Code 方式）

1. 按 `Ctrl + Shift + P` 打开命令面板
2. 输入 `Git: Add Remote`
3. 输入远程名称：`origin`
4. 输入远程 URL：`git@github.com:Fjord-147/-.git`

### 6. 初始化新仓库（VS Code 方式）

1. 打开文件夹后，点击 Source Control 图标
2. 点击 "初始化仓库" 按钮
3. VS Code 会自动执行 `git init`

---

*本仓库已通过命令行完成初始化和推送*
