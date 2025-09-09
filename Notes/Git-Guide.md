# Git 入门与核心工作流指南 

##  Step 1: 前期准备 - 安装与配置 Git 


### 1.1 安装 Git
下载并安装 \[Git for Windows](https://git-scm.com/download/win) 

### 1.2 全局配置 Git 
安装完成后，在终端中执行以下命令进行全局配置（只需配置一次）： 

```bash

# 设置用户名（将"Your Name"替换为您的实际姓名）

git config --global user.name "Your Name"

# 设置邮箱（将"your.email@example.com"替换为您的实际邮箱）

git config --global user.email "your.email@example.com" 
```  

##  Step 2: 克隆操作与提交 

### 2.1 获取仓库地址 

1、访问您的 GitHub 仓库页面 

2、点击绿色的 "Code" 按钮 

3、选择 "SSH" 选项 

4、点击复制图标复制地址（格式：git@github.com:用户名/仓库名.git）

### 2.2 克隆 

```bash 
# 导航到您希望存放项目的目录

cd Documents
# 克隆仓库（将<repository-url>替换为实际地址）

git clone <repository-url>
# 进入克隆下来的仓库目录

cd learning-journal
``` 
### 2.3 提交 

```bash 
# 1. 修改文件后，查看当前状态
git status 

# 2. 将指定文件添加到暂存区
git add Markdown-Tutorial.md 

# 3. 再次查看状态，确认文件已暂存
git status 

# 4. 提交更改到本地仓库
git commit -m "Update: Add today's learning note" 

# 5. 推送更改到远程仓库
git push
``` 
>验证: 完成推送后，刷新 GitHub 仓库页面，您将看到本地添加的内容已同步到远程仓库 

##  Step 3: 总结 
flowchart LR
    A[工作区] -- git add --> B[暂存区]
    B -- git commit --> C[本地仓库]
    C -- git push --> D[远程仓库]

*1、git add*: 将工作区的更改"打包"到暂存区 

*2、git commit*: 给暂存区的更改贴上有说明的"标签"，形成版本快照 

*3、git push*: 将本地版本快照"寄送"到远程仓库 

*4、git clone*: 从远程仓库"获取"完整项目副本到本地 



