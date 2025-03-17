ARG version
FROM almalinux:${version:-8}
ARG COURSE=DEVOPS
ARG TRAINER=sandeep
ARG DURATION=100HR
ENV Duration=${Duration}
RUN echo "Course is: ${COURSE}, Trainer is: ${TRAINER}, Duration is: ${Duration}"
CMD ["sleep","200"]

#docker build -t arg:1.0 --build-arg DURATION=120HERS .