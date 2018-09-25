目录
# git及github设置
## 配置GIT全局name和email
`git config --global vuser.name "name"`  
  `git config --global user.email "email" `
## 配置SSH Key
- 生成SSH Key
<br>`ssh-keygen -t rsa -C "youremail"`
- 将id_rsa.pub内容复制到github
<br>`Settings -> SSH and GPG keys -> New SSH key`
- 测试是否成功
<br>`$ssh -T git@github.com`
## git上传本地代码到github
- github新建Repository
![2018-09-25-20-46-14.png](http://pfm2c79bi.bkt.clouddn.com/2018-09-25-20-46-14.png)
- 更改Settings里GitGub Pages的source为master branch选项可以获取项目静态地址，可以发布静态页面。
![2018-09-25-20-56-06.png](http://pfm2c79bi.bkt.clouddn.com/2018-09-25-20-56-06.png)
- 将要上传的代码放到项目文件夹中
- 执行git add .
- 添加注释语句，执行git commit -m "注释语句"
- 同步到仓库，执行git push origin master
- 刷新仓库地址，可以看到新增的文件已经上传到git上了

# vscode相关插件及设置
- Markdown Preview Enhanced 快捷键改为`Ctrl+K`
- Markdown Shortcuts（待研究）
- Markdown TOC 生成TOC目录
- qiniu-fig-bed 七牛图床 快捷键改为`Ctrl+Q`
# 还未研究的文章 暂时mark
[实用帖 | 如何为 Markdown 文件自动生成目录？](https://www.jianshu.com/p/4721ddd27027)
<br>[如何给VScode配置git](https://www.jianshu.com/p/3c480961210f?from=timeline)
<br>[vscode 插件推荐](https://www.jianshu.com/p/1c178f5c029c)
<br>[Visual Studio Code教程：基础使用和自定义设置](http://www.cnblogs.com/shawWey/p/7908779.html)
<br>[vscode使用Markdown文档编写](https://www.cnblogs.com/shawWey/p/8931697.html)