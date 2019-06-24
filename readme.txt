串口调试相关文档
一、		选择题目：串口调试助手
二、	开发过程
（1）	下载git，在git base中声明用户名称和用户邮箱；
（2）	创建本地仓库；
（3）	初始化git仓库，登入GitHub，新建一个远程库；
（4）	使用ssh通信协议创建一对密钥，把公匙加入GitHub网站的账号中；
（5）	获取sshkey完成匹配；
（6）	链接GitHub，最后将本地库里的文件上传至远程库。
三、	相关的git命令
$ git config --global user.name “gitskill”
$git config --global  user.email “240466730@qq.com”
$ git init（初始化）
$ git add MainWindow.xaml.cs(MainWindow.xaml;readme.txt;readme.docx)（添加文件）
$ git commit -m “wrote a readme file”
$ ssh-keygen -t rsa -C”240466730@qq.com”（获取密钥）
$ git remote add origin git@github.com:AfterOwner/gitskill.git
$ git push -u origin master（上传）
四、上传到GitHub的源代码网址：https://github.com/AfterOwner/gitskill
