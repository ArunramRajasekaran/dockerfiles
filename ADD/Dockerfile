FROM almalinux:9
RUN dnf install nginx -y
ADD https://github.com/ArunramRajasekaran/dockerfiles/blob/main/RUN/Dockerfile /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]