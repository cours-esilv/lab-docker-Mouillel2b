
FROM nginx:alpine

WORKDIR /usr/share/nginx/html

COPY . /usr/share/nginx/html

ENV WS_BACK_URL=http://backend_service_url:5000

ENTRYPOINT ["nginx", "-g", "daemon off;"]