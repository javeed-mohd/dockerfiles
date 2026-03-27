# FROM is used to mention the base OS of the image. It should be the first instruction in Dockerfile.
# Almalinux is exactly same as Redhat Image version 9
# WORKDIR instruction sets the working directory for any RUN, CMD, ENTRYPOINT, COPY and ADD instructions that follow it in the Dockerfile
FROM almalinux:9
RUN mkdir /app
WORKDIR /app
RUN echo "Hello, I am in working directory" > hello.txt