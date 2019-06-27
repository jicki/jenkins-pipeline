# Kubernetes Jenkins Pipeline Config

## jenkins jnlp image

> image Software (Oracle-Jre-1.8 , Gradle-5.4.1 , jenkins-slave-3.19 , docker-18.09.6 )


```
# docker pull

docker pull jicki/jenkins-jnlp:docker


```

```
# ENV 

# gradle 安装目录
GRADLE_HOME = /opt/gradle


# gradle 构建时生成的文件（Cache）
GRADLE_FOLDER=/root/.gradle

# Jenkins 项目构建目录,
HOME=/home/jenkins


```
