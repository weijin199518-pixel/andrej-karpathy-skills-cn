# GitHub仓库创建指南

## 问题
当前GitHub token权限不足,无法通过API创建仓库。

## 解决方案
需要手动创建仓库,或提供新的token(需要`repo`权限)。

## 手动创建步骤

### 1. 访问GitHub创建页面
https://github.com/new

### 2. 填写仓库信息
- **Repository name**: `andrej-karpathy-skills-cn`
- **Description**: `Andrej Karpathy Skills 中文增强版 - 让 Claude 更懂中文开发者`
- **Public/Private**: Public
- **Initialize**: 不要勾选任何选项(README/gitignore/license)

### 3. 点击"Create repository"

### 4. 复制仓库URL
创建后会显示: `https://github.com/weiguopei/andrej-karpathy-skills-cn.git`

## 本地推送命令

创建仓库后,在PowerShell执行:

```powershell
cd "C:\Users\韦国培\.openclaw\workspace\projects\karpathy-skills-cn"
git remote add origin https://github.com/weiguopei/andrej-karpathy-skills-cn.git
git branch -M main
git push -u origin main
```

## 或者:提供新Token

如果想让我自动创建,需要新的GitHub Personal Access Token:

1. 访问: https://github.com/settings/tokens/new
2. 勾选权限: `repo` (完整仓库访问权限)
3. 生成token
4. 提供给我

---

**当前状态**: 本地Git仓库已就绪,等待推送到GitHub
**本地commit**: 730493b (15个文件已提交)
