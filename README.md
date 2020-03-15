# tomcat
Docker-tomcat
## 准备
对于本Dockerfile，需要准备一下文件：
      
- jdk-8u241-linux-x64.tar.gz
- apache-tomcat-8.5.51.tar.gz
       
jdk和tomcat版本可以更换。
         
## 构建
输入以下命令：
        
```bash
chmod 777 Dockerfile    ## 权限

docker bulid ceshi/tomcat:v1 .   ## 构建
```

## 上传镜像
输入以下命令：

```bash
docker tag *****
docker push *****
```        
