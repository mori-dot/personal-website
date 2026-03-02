# 网站部署步骤（GitHub Pages）

## 准备工作

1. 确保您已经修改了网站中的所有填写位内容
2. 准备一个GitHub账号（如果没有，请按照以下步骤注册）

## 步骤1：注册GitHub账号

1. 打开浏览器，访问 https://github.com
2. 点击右上角的"Sign up"（注册）按钮
3. 输入您的邮箱地址，创建密码，选择一个用户名
4. 按照提示完成注册流程，验证邮箱地址

## 步骤2：创建新仓库

1. 登录GitHub账号后，点击右上角的"+"图标，选择"New repository"（新建仓库）
2. 在"Repository name"（仓库名称）中输入您的网站名称，例如 "personal-website"
3. 选择"Public"（公开）选项
4. 勾选"Initialize this repository with a README"
5. 点击"Create repository"（创建仓库）按钮

## 步骤3：上传网站文件

1. 进入刚创建的仓库页面
2. 点击"Add file"（添加文件）按钮，选择"Upload files"（上传文件）
3. 点击"choose your files"（选择文件）按钮，或直接拖拽文件到浏览器窗口
4. 选择您本地的网站文件（index.html、about.html、README.md、DEPLOY.md）
5. 等待文件上传完成
6. 在页面下方的"Commit changes"（提交更改）部分，输入一个简单的提交信息，例如"Add website files"
7. 点击"Commit changes"（提交更改）按钮

## 步骤4：启用GitHub Pages

1. 在仓库页面中，点击顶部的"Settings"（设置）选项卡
2. 在左侧菜单中，点击"Pages"
3. 在"Source"（源）部分，点击下拉菜单，选择"main"分支
4. 点击"Save"（保存）按钮
5. 页面会刷新，显示"Your site is ready to be published"（您的网站已准备好发布）
6. 等待几分钟，然后刷新页面，您会看到一个绿色的"Your site is published at"（您的网站已发布在）消息，后面跟着您的网站URL

## 步骤5：访问您的网站

1. 复制GitHub Pages提供的URL
2. 打开浏览器，粘贴该URL并访问
3. 您的网站现在应该可以正常访问了

## 常见问题解决

### 网站不显示或显示错误

- 确保所有文件都已正确上传
- 等待10-15分钟，GitHub Pages可能需要一些时间来部署您的网站
- 检查文件名称是否正确（index.html和about.html）

### 导航链接不工作

- 确保index.html和about.html在同一目录下
- 检查链接路径是否正确（使用相对路径）

## 其他部署选项

如果您不想使用GitHub Pages，也可以考虑使用Gitee Pages（国内访问速度更快），步骤类似：

1. 注册Gitee账号：https://gitee.com
2. 创建仓库并上传文件
3. 在仓库设置中启用Gitee Pages

## 部署完成

恭喜！您的个人官网已经成功部署到GitHub Pages，可以通过外部链接访问。如果您需要更新网站内容，只需修改本地文件后重新上传到GitHub仓库即可。