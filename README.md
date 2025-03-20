[Guide](https://cwiki.apache.org/confluence/display/KAFKA/KIP-653%3A+Upgrade+log4j+to+log4j2)

Migration log4j 1 to log4j 2: 
```sh
java -cp "/path/apache-log4j2/log4j-1.2-api-2.24.3.jar:/path/apache-log4j2/log4j-core-2.24.3.jar:/path/apache-log4j2/log4j-api-2.24.3.jar" org.apache/log4j/config.Log4j1ConfigurationConverter -i=log4j.properties -o=log4j2.xml
```
