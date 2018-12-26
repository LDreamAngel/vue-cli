# vue-cli
vue项目的搭建与axios封装，不同环境的域名配置

#vue环境搭建

第一步 node环境安装
  1.1 如果本机没有安装node运行环境，请下载node 安装包进行安装
  1.2 如果本机已经安装node的运行换，请更新至最新的node 版本
      下载地址：https://nodejs.org/en/ 或者 http://nodejs.cn/

第二步 node环境检测
   为了快乐的使用命令行，我们推荐使用 gitbash
   1.1 下载git 并安装
       下载地址 https://git-for-windows.githu...
       安装成功后 右键菜单
       我们可以看到 Gti Bash Here 。说明我们已经安装成功git

   1.2 检测node 是否安装成功
       右键空白，选择 Gti Bash Here 弹出

       1.2.1 在终端输入 node -v
             如果输出版本号，说明我们安装node 环境成功
             随便我们可以查看 npm 的 版本号
             可以使用 npm -v

第三步 vue-cli脚手架安装
  2.1 如果访问外网比较慢，可以使用淘宝的镜像 https://npm.taobao.org/
      打开命令终端 npm install -g cnpm --registry=https://registry.npm.taobao.org
      回车之后，我就可以可以快乐的用 cnpm 替代 npm
      你已经成功安装了 cnpm
      但是此后，我们还是使用 npm 来运行命令

  2.2 接下来就是重点了 安装vue-cli
      npm install vue-cli -g

  2.3vue-cli的项目搭建详情请参见：
      https://www.cnblogs.com/superlizhao/p/8664326.html

注：桌面打开git bash 检查安装即可；