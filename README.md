# maven-repo
      this is my maven repository created by github

user guide
-----------------------------------
### maven
      <repositories>
        <repository>
            <id>yan-maven-repo</id>
            <url>https://raw.githubusercontent.com/yan1234/maven-repo/master/repository</url>
        </repository>
      </repositories>
### gradle
      repositories {  
          maven { 
            url "https://raw.githubusercontent.com/yan1234/maven-repo/master/repository" 
          }  
      }
repository
-----------------------------------
####   条码扫描组件
######  V1.0: 提供基本的条码扫描功能，支持Zxing,Zbar,条码生成，相机画面解析为bitmap等功能模块      
      <dependency>
            <groupId>com.yanling.android</groupId>
            <artifactId>scanlibrary</artifactId>
            <version>1.0</version>
      </dependency>
