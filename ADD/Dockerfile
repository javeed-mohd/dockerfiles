# FROM is used to mention the base OS of the image. It should be the first instruction in Dockerfile.
# Almalinux is exactly same as Redhat Image version 9
# ADD and COPY both are used to copy the files from local to image, but ADD has 2 extra capabilities,
# 1. It can fetch the content directly from internet.
# 2. It can untar(extracts) the content directly in the image.
FROM almalinux:9
ADD https://raw.githubusercontent.com/daws-88s/roboshop-documentation/refs/heads/main/01-mongodb.MD /tmp/
ADD sample-1.tar /tmp/