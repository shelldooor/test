# test

# main分支做出的修改,saac


main分支修改的内容

Github网站上修改的分支


![github学习框架](https://gitee.com/shell101/picgo/raw/master/markdown/Blogs/github学习框架_20250108_1001.png)

---

# 1.Github：

版本控制，远端仓库，类似的还有gitlab，gitbucket

## github加速方法

1. 下载watt toolkit（原名为steam++），网址为：https://steampp.net，找到github一键加速即可
2. github上的开源工具：dev sidecar

# 2.Github网站基础

1. 网页中的操作按钮汉化——github-Chinese（利用油猴运行脚本）

2. 网页中的大段英文翻译——edge插件：沉浸式翻译

3. 快捷键

   - /快速打开搜索栏
   - 在代码页面，快捷键T快速搜索代码文件
   - 打开代码文件之后，快捷键L快速定位到某一行代码
   - 快捷键？（shift + /就是问号？）可以快速查看所有的快捷键
   - 快捷键。会打开一个网页版的vscode，可以在线调试代码(Creat New Codespace)，不过每个用户每个月免费时长有限（120h）

4. watch指的是关注项目，接受项目的更新信息（通过**邮件**的方式发布）

5. star既是点赞也是收藏

6. fork就是**复刻一份副本**到自己的仓库下，自己可以随意更改（还可以同步源项目到自己仓库中），然后可以通过pull requset请求和原有的项目进行合并

7. 订阅作者或者组织，在自己的主界面可以看到自己的关注（following），和自己的关注者（followers）

8. releases：下载不同版本的软件安装包

   - 安装包的命名规则：软件名-版本号-操作系统-CPU架构

     > 操作系统包括：Linux、Windows、FreeBSD、Android、MacOS==Darwin（macOS的技术基础和底层框架）
     >
     > cpu架构：x86_64==AMD64==x64(大部分个人电脑和服务器)、arm(大部分的智能手机和新款苹果电脑)、RISC-V、MIPS

   - 有的软件并没有提供releases，可以去项目简介中找找项目的官网

   - 还可以使用docker

   - 下载代码自行运行

     > 1. 下载或者克隆代码到本地
     > 2. 安装运行的环境
     > 3. 安装依赖
     > 4. 找到入口文件，启动（例如python一般是main文件，一般在readme文档中会有，有问题可以看看issue）

9. 新建仓库的时候选择的开源协议

   > GPL：别人fork代码进行修改之后必须也开源，缺点就是具有传染性，只要用了部分他的代码，整个项目就得开源，例如：linux、wordpress、Git等等
   >
   > GUN：
   >
   > 

   ![开源协议](https://gitee.com/shell101/picgo/raw/master/markdown/Blogs/开源协议_20250108_2303.png)

   **gitignore文件：后面会讲**

# 3.Github中寻找有趣的项目

1. https://github.com/explore页面，包含github的介绍，热搜
2. https://github.com/search页面，可以进行搜索，例如TTS（文字转语音）
   - 高级搜索，可以使用UI限定作者、语言、日期、star数、开源许可证、是是否查看fork出来的项目、文件扩展名、issue等内容，它会自动生成高级搜索语句
3. https://github.com/stars页面，查看所有star过的项目，star既是点赞也是收藏

