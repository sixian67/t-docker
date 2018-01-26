FROM registry.cn-hangzhou.aliyuncs.com/taoke/centos-systemd:7
MAINTAINER taoke <szy361@126.com>
RUN mkdir -p /home/nodejs/
COPY . /home/nodejs/
WORKDIR /home/nodejs/
RUN tar -zxvf node-v6.12.3-linux-x64.tar.gz
RUN ln -s /home/nodejs/node-v6.12.3-linux-x64/bin/node /usr/local/bin/node
RUN ln -s /home/nodejs/node-v6.12.3-linux-x64/bin/npm /usr/local/bin/npm
RUN echo -e "export PATH=$(npm prefix -g)/bin:$PATH" >> ~/.bashrc && source ~/.bashrc
RUN npm install -g cnpm --registry=https://registry.npm.taobao.org
RUN rm -rf node-v6.12.3-linux-x64.tar.gz

