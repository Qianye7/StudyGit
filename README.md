# StudyGit 
### linux命令  
```
*nkdir  
*cd..  
*ls -la  
*ZZ  //保存退出vim  
*:x , :wq 
```
### vim编辑器  
1.打开终端  
输入`vim + 文件名`打开文件  
2.输入信息  
输入`i`进入编辑  
3.退出保存  
`esc`切换模式后，输入`：wq`保存退出  
`:wq , ZZ 保存退出`  
4.设置行号
`:set nu`  
### Mac下无ll命令如何办  
就是起别名操作
设置别名  
1、(Mac环境)编辑` vim ~./bash_profile`              
2、设置ll别名
文件中添加
  ```
        `alias ll='ls -alF'  

         alias la='ls -A'  
         
         alias l='ls -CF” ` 
   ```        
3、生效操作  
`sudo source ~/.bash_profile`
#### git bash(来自网络)  
```
1、bash命令格式

命令 [-options]  [参数]，如：tar  zxvf  demo.tar.gz

查看帮助：命令 --help

2、bash常见命令

pwd (Print Working Directory) 查看当前目录

cd (Change Directory) 切换目录，如 cd /etc

ls (List) 查看当前目录下内容，如 ls -al

mkdir (Make Directory) 创建目录，如 mkdir blog

touch 创建文件，如 touch index.html

cat 查看文件全部内容，如 cat index.html

more/less 查看文件，如more /etc/passwd、less /etc/passwd

rm (remove) 删除文件，如 rm index.html、rm -rf  blog

rmdir (Remove Directory) 删除文件夹，只能删除空文件夹，不常用

mv (move) 移动文件或重命名，如 mv index.html ./demo/index.html

cp (copy) 复制文件，cp index.html ./demo/index.html

head 查看文件前几行，如 head -5 index.html

tail 查看文件后几行 –n –f，如 tail index.html、tail -f -n 5 index.html

tab 自动补全，连按两次会将所有匹配内容显示出来

history 查看操作历史

> 和 >>重定向，如echo hello world! > README.md，>覆盖 >>追加

wget 下载，如wget https://nodejs.org/dist/v4.4.0/node-v4.4.0.tar.gz

tar 解压缩，如tar zxvf node-v4.4.0.tar.gz

curl 网络请求，如curl http://www.baidu.com

whoami 查看当前用户

| 管道符可以将多个命令连接使用，上一次（命令）的执行结果当成下一次（命令）的参数。

grep 匹配内容，一般结合管道符使用  
```
### 补充  
1. 从缓冲区删除` git rm --cached [file name]`
### 练习  
![pic](https://github.com/Qianye7/huashan/blob/master/u%3D716017398%2C429203332%26fm%3D26%26gp%3D0.jpg)  
![img](https://github.com/Qianye7/huashan/blob/master/u%3D716017398%2C429203332%26fm%3D26%26gp%3D0.jpg)
