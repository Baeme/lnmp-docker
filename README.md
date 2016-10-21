# lnmp-docker

## 镜像列表

1. nginx（office）
2. php（chunhei2008/php）
3. memcached（office）
4. redis（office）
5. beanstalkd（schickling/beanstalkd）
6. mysql (office)
7. phpmyadmin (phpmyadmin/phpmyadmin)

## 使用

1. docker-compose up	第一次启动
2. docker-compose start 启动
3. docker-compose stop  停止
4. docker-compose rm    删除停止的容器

## 备注

1. nginx和php的容器请同时挂在本地相同的目录到相同的挂载点，这样在处理php文件和其他静态文件时在同一个目录下，php的文件处理是通过php在php的容器中进行查找的，其他静态文件是nginx在nginx容器下查找的

