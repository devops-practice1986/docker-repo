FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://github.com/devops-practice1986/expense-infra-dev-2/blob/main/.gitignore /usr/share/nginx/html/index.html
#RUN chmod +x /usr/share/nginx/html/index.html
CMD [ "nginx", "-g", "daemon off;" ]
