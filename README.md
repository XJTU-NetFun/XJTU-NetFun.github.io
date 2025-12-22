# ANTS NetFun网站后台
## 修改信息
### 如何提交
1. clone到本地
2. 从main分支中创建自己的分支，修改完提交pull request
3. 等待merge到main分支中。如果长时间没有改动，请联系maintainer

### 修改个人信息
1. content/en中的个人信息。每个人创建自己的md文件
2. 头像在static/people中。注意修改content/en中的头像路径
3. 不需要在这里填写论文信息。在content/paper中的论文附带有个人信息，会自动更新到个人主页
4. md文件中的date决定了页面上人员的排序，建议修改成自己的入学时间，例如2025-09-01

### 修改论文
1. content/paper中的论文信息。每个论文创建一个md文件
2. 论文pdf在static/paper中。注意修改content/paper中的pdf路径

### 修改网站主页信息
大多数在hugo.toml中修改。建议查找文件名的字符串

参考网站：https://xjtu-netverify.github.io/

查找图片：在浏览器的开发者页面中查找图片名称，然后使用grep -r在本路径下查找

查找文字：直接grep -r查找


# 以下信息针对maintainer
## 部署问题
### 如何部署
main分支修改后，github会自动运行。大约30秒后网站会更新。
如果没有更新，请在仓库的action页面查看问题

### 从零开始部署网站
fork之后，在Settings->Pages->Build and deployment->Source中选择gh-pages分支，保存。即可自动部署

### 注意事项
1. 任何情况都不需要修改gh-pages分支，只需要修改main分支
2. 如果action出错，则不会修改网站；如果不报错，则会自动直接部署
3. XJTU-NetFun的创建人为李芝塬，联系方式：zyli, knowncircle@163.com。
4. 除了权限问题，不建议找我，大概率没啥用，因为这个项目是我fork来的，我也看不懂。
5. 文件名应当尽可能简洁，避免除`-_.`之外的特殊符号。



