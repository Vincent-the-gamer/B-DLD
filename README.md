# B-DLD
Use Come Under Load B Stand Television Channel

## 隐私豆儿累神 (Installation)
Download setup from releases to install:

[瑞离~斯（Release)](https://github.com/Vincent-the-gamer/B-DLD/releases)

## 在Node项目中使用Electron的注意事项

如果需要使用Electron来打包桌面应用程序，需要用到electron和electron-builder两个库

~~~shell
npm install electron
npm install electron-builder
~~~

在调试和打包项目的时候，需要下载对应的依赖包，但是它默认的库是github的，容易崩，所以我预先打包了

[下载Electron依赖包](./electron依赖包.zip)

然后解压后放在以下路径中

**PS：如果放进去没有用，还是提示下载，那肯定是Electron库默认依赖版本发生变化，请手动去GitHub下载对应版本来完成以下操作**

Windows:

~~~
# Windows
C:\Users\你的用户名\AppData\Local\electron\Cache
~~~

文件夹目录层级注意：

~~~
- nsis
- winCodeSign
- electron-v16.2.8-win32-x64.zip
~~~

macOS/Linux等：

通常是在用户文件夹中找，先运行一下程序，让它安装，然后中断安装，这样就生成了electron路径，找到里面有Cache文件夹的即可，然后记得专门去下载对应版本的以下内容

~~~
- nsis(macOS/Linux版，注意架构和操作系统位数的对应)
- winCodeSign(macOS/Linux版，注意架构和操作系统位数的对应)
- electron-v16.2.8(macOS/Linux版，注意架构和操作系统位数的对应)
~~~
