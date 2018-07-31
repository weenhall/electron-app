## 使用Electron开发环境设置
* 安装nodejs
* 安装electron
* 安装electron-package

## 项目依赖添加
  * 切换到项目根目录打开cmd  
  
  
      nmp install mysql --save
    
## 项目打包  
  * 手动打包
  
  
     electron-packager <sourcedir> <appname> --platform=<platform> --arch=<arch>
     npm run packager 
  
  * 半自动打包
     在package.json中配置
     
     
     "srcipts":
     {""package":"electron-packager ./ start --win --out outApp --arch=x64 --electron-version 2.0.5 --overwrites"}
     
     npm run packager
 