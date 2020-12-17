FROM nginx

RUN apt-get update && apt-get install -y git
RUN mkdir -p /etc/2048 && cd /etc/2048 && git clone https://gitlab.com/bliznetz/devops.git
RUN cp -r /etc/2048/devops/2048/* /usr/share/nginx/html
