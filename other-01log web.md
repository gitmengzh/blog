# 根据log需求，写一个工具
## 需求 ##
    由于log在aws中s3服务器，查看起来比较麻烦，现在做一个log查看的web工具，实现一下功能
    1. web系统
    2. 下载制定时间log
    3. 更新log
    4. 查询log

## 方案 ##
    1 使用s3命令拷贝log
    2 web端使用flask
    3 不使用数据库，研究一下，直接用linux或者python查询log文件，不记录