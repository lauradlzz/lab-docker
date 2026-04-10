FROM nginx:alpine

WORKDIR /usr/share/nginx/html

COPY . .

ENV WS_BACK_URL=http://localhost:5000

ENTRYPOINT ["sh", "entrypoint.sh"]