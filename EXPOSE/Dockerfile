# FROM is used to mention the base OS of the image. It should be the first instruction in Dockerfile.
# Almalinux is exactly same as Redhat Image version 9
# RUN instruction is used to install packages or configure image.
# EXPOSE is useful to display the port information of container. It will not really open the port but provides information only to the users.
FROM almalinux:9
RUN dnf install nginx -y
EXPOSE 80
CMD ["nginx","-g","daemon off;"]