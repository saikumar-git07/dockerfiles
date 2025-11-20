ARG version
FROM almalinux:${version:-8}
#RUN cat /etc/*release
ARG COURSE
ARG TRAINER
# ARG Duration=120HRS
# ENV Duration=${Duration}
RUN echo "Course is: ${COURSE}, Trainer is: ${TRAINER} "
CMD [ "sleep", "100" ]