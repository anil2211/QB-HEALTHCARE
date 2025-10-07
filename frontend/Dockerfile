# build static site image
FROM nginx:stable-alpine
COPY ./index.html /usr/share/nginx/html/index.html
# optional: copy css / assets if any
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
