FROM nginxinc/nginx-unprivileged:1-alpine        

# copy the default.conf/uwsgi_params files into location in the docker container 
# that nginx expects to finds a configuration
COPY ./default.conf /etc/nginx/conf.d/default.conf 