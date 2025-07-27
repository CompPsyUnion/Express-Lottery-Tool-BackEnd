# 简单的抽奖工具后端
  🌍 **中文** | [English](/README_en.md) 

此工具已更新殆尽，已归档。  
现在已经开发了重制版，功能更丰富，支持后台管理，多活动配置等功能：[https://github.com/buduan/Lottery-Tool-Backend](https://github.com/buduan/Lottery-Tool-Backend)

使用Node.js + MongoDB构建 支持运行在腾讯云Serverless服务  
要用的前一天晚上，两个人熬夜肝出来的，所以admin的api也没做鉴权，后续会加。  
求Star～✨

## 关联项目
前端Github项目：  
前端推荐使用Electron构建app，或者使用PWA下载到设备使用，无需部署。  
前端Github项目👉[https://github.com/buduan/CPU-Lottery-Tool-FrontEnd/](https://github.com/buduan/CPU-Lottery-Tool-FrontEnd/)  
后台前端Github项目👉[https://github.com/CompPsyUnion/GiftDrewAdminFE/](https://github.com/CompPsyUnion/GiftDrewAdminFE/)   
后台可部署到腾讯云静态网站托管服务等类似服务中。  

## 如何安装  
首先需要在你的服务器上准备node.js环境和MongoDB数据库管理软件。

然后新建项目目录，克隆此仓库到你的项目目录中

修改app.js中的数据库连接方式（地址、端口、用户名、密码）

在终端运行
```
node app.js
```
后续会封装成可执行文件，以及适配Cloudflare Workers。

## API文档地址
接口请前往👉[ApiFox](https://app.apifox.com/project/5639349)查看
