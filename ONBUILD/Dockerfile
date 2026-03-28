# FROM is used to mention the base OS of the image. It should be the first instruction in Dockerfile.
# Almalinux is exactly same as Redhat Image version 9
# RUN instruction is used to install packages or configure image.
# We want to put some conditions to use our image for others, then that can be enforced using ONBUILD instruction.
# Our nginx image expects index.html while it is used by others.
FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ONBUILD COPY index.html /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]