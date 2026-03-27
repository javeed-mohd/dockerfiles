# FROM is used to mention the base OS of the image. It should be the first instruction in Dockerfile.
# Almalinux is exactly same as Redhat Image version 9
# ENTRYPOINT is used to provide the command executed by the container when it is started.
# We can override the command inside CMD instruction at run time. We can't override ENTRYPOINT command, If you try to do so it will go and append.
# For best results, we can always use both CMD and ENTRYPOINT
FROM almalinux:9
# CMD ["ping","google.com"]
# ENTRYPOINT ["ping","google.com"]
CMD ["google.com"]
ENTRYPOINT ["ping"]