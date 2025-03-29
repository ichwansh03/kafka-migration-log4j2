[Log4j Migration](https://cwiki.apache.org/confluence/display/KAFKA/KIP-653%3A+Upgrade+log4j+to+log4j2)

[Slf4j Migration](https://cwiki.apache.org/confluence/display/KAFKA/KIP-1064%3A+Upgrade+slf4j+to+2.x)

Log4j properties converter: 
```sh
java -cp "/path/apache-log4j2/log4j-1.2-api-2.24.3.jar:/path/apache-log4j2/log4j-core-2.24.3.jar:/path/apache-log4j2/log4j-api-2.24.3.jar" org.apache/log4j/config.Log4j1ConfigurationConverter -i=log4j.properties -o=log4j2.xml
```
