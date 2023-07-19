安装说明

zookeeper
需要事先下载好Java 安装包到 bin 目录。我这里使用的是 Oracle 的 jdk，如果使用 open-jdk 则需要更改 roles/zookeeper/tasks/main.yml 文件的包名（包含软件中的解压后的包名）。

下载zookeeper 安装包到 bin 目录。  
https://zookeeper.apache.org/releases.html

Docker
下载 Docker 二进制安装包到 bin 目录，并运行playbook docker.yml   
默认 Docker 版本为24.0.2   
https://download.docker.com/linux/static/stable/x86_64/
