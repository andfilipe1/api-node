
# Set nginx base image


FROM jwilder/nginx-proxy

COPY api.conf /etc/nginx/conf.d/eou.conf
COPY efault.conf /etc/nginx/conf.d/default.conf
COPY nginx.conf /etc/nginx/nginx.conf
COPY logrotate_nginx /etc/logrotate.d/nginx


