from openresty/openresty:centos
copy nginx_redis.conf /usr/local/openresty/nginx/conf/nginx.conf
RUN yum install gcc -y
RUN luarocks install luasocket