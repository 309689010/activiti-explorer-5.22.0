### 启动步骤
```$xslt
1、修改db.properties 数据库相关参数
2、部署项目到tomcat
3、默认登陆账号:kermit 、 密码:kermit
```

### FAQ
```$xslt
如果遇到编辑流程图时工具栏页面都是空白的， 将app-cfg的contextRoot改为项目部署名
如: 
   ACTIVITI.CONFIG = {
   	'contextRoot' : '/your project name/service',
   };
```
