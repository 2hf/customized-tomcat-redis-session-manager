# customized-tomcat-redis-session-manager

This project helps you to customized your own redis cache in tomcat web application, simply adding your very own prefix to redis key like this in `Tomcat/conf/server.xml`

```xml
<Context docBase="/root/YOUR_WEB_APP" 
	path="" 
	reloadable="true" 
	sessionCookieName="YOURJSessionID" />
```


