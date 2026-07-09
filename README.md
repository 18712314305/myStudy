# myStudy 仓库

## 1. 目录结构

- AboutDeepLearning：深度学习相关

    - PyTorch

- AboutMath: 数学基础相关

    - Statistics


## 2. 子模块操作

### 2.1 如何创建新的子模块(学习仓库)

1. 在 github 上创建空白目录, 并添加 readme 文件, 保持命名规范 `mystu-name`, 注意统一主分支为 `master`
2. 在 myStudy 主仓库目录下, 使用 submodule 命令添加子模块, 如: 
```git submodule add git@github.com:yFeiLu/mystu-Statistics.git targetPath```
3. 此时, 远程的子仓库会被克隆到 `targetPath`,  后续在该子仓库中维护即可
4. 主仓库提交并推送
