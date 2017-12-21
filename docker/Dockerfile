FROM registry.cn-hangzhou.aliyuncs.com/xinchen0618/lnmp:latest

COPY default.conf /etc/nginx/conf.d/default.conf

RUN git clone -b v1.6.1 https://git.coding.net/chenxin0704/hello-k8s.git

CMD ["supervisord"]