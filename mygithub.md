## github笔记

创建公钥

```git
ssh-keygen -o
```



enter键继续，输入y，接着enter键，enter键



复制公钥key添加到github，文件路径图中已显示 Your public key has been saved in /c/Users/zhoudaozhi/.ssh/id_rsa.pub



复制路径并打开

```git
cat /c/Users/zhoudaozhi/.ssh/id_rsa.pub
```



得到公钥，开始复制ssh-rsa AAA...添加到github



github设置选项进去左边有个SSH and GPG keys，点击后右边就可以加入了