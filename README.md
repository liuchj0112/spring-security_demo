# spring-security_demo
spring-security的demo案例

注意：
1.WEB-INF/web.xml中的<url-pattern>/*</url-pattern>是spring-security的入口，表明拦截一切资源
2.WEB-INF/web.xml中的<filter-name>springSecurityFilterChain</filter-name>的springSecurityFilterChain不可更改
3.resource/spring-security.xml中的<intercept-url pattern="/**" access="ROLE_USER" />表明拦截当前根目录及子目录下的资源

