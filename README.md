# 项目简介

**models:**存放操作数据库的文件   

**public:** 存放静态文件文件，如样式、图片等  

**routes:** 存放路由文件  

**views:** 存放模板文件  

**index.js:** 程序主文件  

**package.json:** 存储项目名、描述、作者、依赖等等信息  

**config:**存放配置文件  

**middlewares:**存放权限控制的中间件  


安装依赖
```
npm i config-lite connect-flash connect-mongo ejs express express-formidable express-session marked moment mongolass objectid-to-timestamp sha1 winston express-winston --save
```

**express:** web 框架  

**express-session:** session 中间件  

**connect-mongo:** 将 session 存储于 mongodb，结合 express-session 使用  

**connect-flash:** 页面通知提示的中间件，基于 session 实现  

**ejs:** 模板  

**express-formidable:** 接收表单及文件的上传中间件  

**config-lite:** 读取配置文件  

**marked:** markdown 解析  

**moment:**时间格式化  

**mongolass:** mongodb 驱动  

**objectid-to-timestamp:** 根据 ObjectId 生成时间戳  

**sha1:**sha1 加密，用于密码加密  

**winston:** 日志  

**express-winston:** 基于 winston 的用于 express 的日志中间件  
