# COPY is used to copy the files from local to image.
FROM nginx:1.29.7
RUN rm -f /usr/share/nginx/html/index.html
# index.html -> local, There already a default nginx will be present so we use remove command.
COPY index.html /usr/share/nginx/html