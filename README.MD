# 可以使用该package制作简单的企业站

#特点
- 命令简单
- 可配置
- 本地注入数据
- 一键发布
- 类似于本地cms

# 使用流程
1、site init 
```
-site1
--config.json:配置文件,后面细说
--index.html:首页
--images/:图片目录
--styles/:样式目录
--scripts/:脚本目录
--components/:组件目录

---header/
----index.html
----index.js
----index.scss

---footer/
----index.html
----index.js
----index.scss

--data
---data1.json:读取改文件的数据
---data2.js:异步数据
```
2、site serve [site1,site2,site3]:本地开发
3、site build:生成部署文件
4、site deploy:部署