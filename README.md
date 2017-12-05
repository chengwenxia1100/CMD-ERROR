Solving the mistake of reporting in CMD
Node -v  显示  10106(无法加载或初始化请求的服务提供程序)
解决方案：
在命令提示符右键以管理员身份打开后，输入netsh winsock reset，然后重启计算机即可。



在vue创建之后输入npm install报错的（npm ERR! Unexpected end of JSON input while parsing near '...e":"ejs","version":"0'）
解决方案：
运行npm cache clean --force
