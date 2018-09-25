目录
# git及github设置
## 配置GIT全局name和email
`git config --global user.name "name"`  
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
![2018-09-25-20-46-14.png](http://pfm2c79bi.bkt.clouddn.com/2018-09-25-20-46-14.png)markdown-preview-enhanced