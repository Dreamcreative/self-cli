# 自己创建一个 cli 脚手架

1. npm init :初始化项目
2. npm link :在本地开发 npm 模块的时候，使用 npm link,将 npm 模块链接到对应的运行项目中去，方便对模块进行调试和测试
3. 创建一个 bin 目录，同时创建一个 mx 文件(没有后缀,可以是任意的名称)
4. 在 mx 文件内进行 cli 的各种代码编写
5. 使用commander包，来执行命令行
6. 使用shelljs包，来执行shell脚本
7. 使用download-git-repo包来下载git项目
8. 使用json2ts来生成ts接口
9. 使用node原生模块child_process来开启子进程，来下载项目依赖包