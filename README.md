# FireMutttttt

这是一个使用 Unreal Engine 开发的第一人称射击游戏项目。

## 项目要求

- **Unreal Engine 版本**: 请根据项目文件确认版本
- **操作系统**: Windows / macOS / Linux
- **Git LFS**: 必需（用于处理大文件）

## 克隆和设置

本项目使用 Git LFS 来管理大文件。在克隆仓库之前，请确保已安装 Git LFS。

### 1. 安装 Git LFS

```bash
# Windows (使用 Git 安装程序，通常已包含 LFS)
git lfs install

# macOS (使用 Homebrew)
brew install git-lfs
git lfs install

# Linux (Ubuntu/Debian)
sudo apt-get install git-lfs
git lfs install
```

### 2. 克隆仓库

```bash
git clone https://github.com/YOUR_USERNAME/FireMutttttt.git
cd FireMutttttt
```

### 3. 确认 LFS 文件已下载

```bash
git lfs pull
```

## 打开项目

1. 右键点击 `FireMutttttt.uproject` 文件
2. 选择 "Switch Unreal Engine version..." 或直接用 Unreal Engine 打开
3. 如果提示重新编译模块，点击 "Yes"

## 项目结构

- **Content/FirstPerson**: 第一人称模式的关卡和资源
- **Content/Variant_Shooter**: 竞技场射击模式的关卡和资源
- **Content/Weapons**: 武器系统（手枪、步枪、榴弹发射器）
- **Content/Characters/Mannequins**: 角色模型
- **Content/Input**: 输入映射配置

## 游戏模式

本项目包含两个游戏模式：
1. **第一人称模式** (`Lvl_FirstPerson`)
2. **竞技场射击模式** (`Lvl_ArenaShooter`)

## 贡献

欢迎提交 Pull Request 或报告 Issues。

## 许可证

[请添加你的许可证信息]
