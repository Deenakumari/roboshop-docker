FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
RUN /etc/nginx/nginx.conf
ADD nginx.conf /etc/nginx/nginx.conf
ADD static/* /usr/share/nginx/html/index.html