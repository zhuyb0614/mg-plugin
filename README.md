# mg-plugin
mybatis-generator 扩展

##使用方法
项目pom引入plugin并且依赖本项目,在resources目录放入generator.properties
,generatorConfig.xml并修改配置即可
```xml
            <plugin>
                <groupId>org.mybatis.generator</groupId>
                <artifactId>mybatis-generator-maven-plugin</artifactId>
                <version>1.3.6</version>
                <configuration>
                    <verbose>true</verbose>
                    <overwrite>true</overwrite>
                    <includeAllDependencies>true</includeAllDependencies>
                </configuration>
                <dependencies>
                    <dependency>
                        <groupId>org.rainbow</groupId>
                        <artifactId>mg-plugin</artifactId>
                        <version>1.0-SNAPSHOT</version>
                    </dependency>
                </dependencies>
            </plugin>
```
