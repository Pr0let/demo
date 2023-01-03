# tduck部署
### 前后端源码  
git clone https://gitee.com/TDuckApp/tduck-platform.git  
git clone https://gitee.com/TDuckApp/tduck-front.git
### docker环境安装
source get-docker.sh  
pip install docker-compose
### docker-compose启动容器
docker-compose up -d
### 关闭防火墙
systemctl stop firewalld  
systemctl disable firewalld
