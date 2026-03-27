# FROM is used to mention the base OS of the image. It should be the first instruction in Dockerfile.
# Red Hat Universal Base Image 9
# RUN instruction is used to install packages or configure image.
# CMD is used to run the container. It is executed at the time of running the container. We can have multiple RUN instructions inside dockerfile. But only one CMD instruction.
FROM redhat/ubi9
RUN dnf install nginx -y
CMD ["nginx","-g","daemon off;"]