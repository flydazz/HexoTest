---
title: HexoStudy
date: 2020-06-24 20:20:05
categories: 
    - Study Notes
tags: 
    - hexo
    - note
---
# 官方链接
[Hexo中文网](https://hexo.io/zh-cn/ "Hexo")

# 安装
```
npm install hexo-cli -g
```
# 初始化
```
hexo init <目录名>
cd <目录名>
npm install
```
# 生成静态文件
```
hexo generate
```
也可以简写为
```
hexo g
```
# 启动服务器
```
hexo server
```
默认情况下，访问网址为： http://localhost:4000/ 。


|  选项   | 描述  |
|  ----  | ----  |
| -p, --port  | 重设端口 |
| -s, --static  | 只使用静态文件 |
| -l, --log  | 启动日记记录，使用覆盖记录格式 |
该命令可以简写为
```
hexo s
```
# 部署网站
```
hexo deploy
```
也可以简写为
```
hexo d
```

