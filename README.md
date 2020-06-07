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

