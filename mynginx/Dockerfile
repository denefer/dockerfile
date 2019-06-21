FROM nginx
# 容器运行后将显示本容器的ID
CMD hostname > /usr/share/nginx/html/index.html \
    && nginx -g 'daemon off;'
