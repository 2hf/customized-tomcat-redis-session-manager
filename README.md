# customized-tomcat-redis-session-manager

Adding your very own prefix to redis key like this in `Tomcat/conf/server.xml`

```xml
<Context docBase="/root/YOUR_WEB_APP" 
	path="" 
	reloadable="true" 
	sessionCookieName="YOURJSessionID" />
```


