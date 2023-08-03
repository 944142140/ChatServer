# ChatServer
使用nginx tcp 负载均衡环境中的集群聊天服务器和客户端 基于muduo实现

编译方式
cd build
rm -rf *
cmake ..
make

注意需要安装Json开发库 Json.hpp
安装boost+muduo网络库开发环境
安装redis，mysql数据库环境
安装nginx
