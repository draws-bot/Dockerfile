#this is my own image#
FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ONBUILD COPY index.html /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]


#this is  useful as trigger , if someone is trying to use your images .you can force them to keep somefiles in their workspace or configuration