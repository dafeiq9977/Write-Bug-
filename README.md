# Write-Bug
README.md叙述了实习期间遇到的问题和解决方案
## 1. VScode powershell不允许运行脚本解决方案
以管理员打开身份打开powershell，执行`set-ExecutionPolicy RemoteSigned`命令，执行`get-ExecutionPolicy`查看修改结果  
或者  
更改VSCode终端为cmd(默认是powershell)  
![pic1](https://github.com/dafeiq9977/Write-Bug/tree/main/pic/pic1.jpg)
## 2. 开发环境常用命令
npm install <pkg name> --save   下载包，并保存到package.json中  
tsc --init  生成tsconfig.json文件  
