# ARG can be first instruction in a special case to supply the version to base image.
ARG version
FROM almalinux:${version:-8}
ARG COURSE="Docker" \
    DURATION="12 Hours" \
    SOURCE="Amazon Web Services"
RUN echo "Course is: ${COURSE}, Version is: ${version}"
CMD ["sleep","200"]