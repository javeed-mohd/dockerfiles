# FROM is used to mention the base OS of the image. It should be the first instruction in Dockerfile.
# Almalinux is exactly same as Redhat Image version 9
# RUN instruction is used to install packages or configure image.
FROM almalinux:9
RUN dnf install nginx -y
# Root access required to create user or install packages
RUN useradd roboshop

USER roboshop
CMD["sleep","100"]