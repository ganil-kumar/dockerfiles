#ARG provide variables to image
#ARG can be first instruction in a special case to supply the version to base image	
ARG version
FROM almalinux:${version:-8}
ARG COURSE="Docker" \
    TRAINER="Sivakumar" \
    DURATION="10HRS" \
     AUTHOR="joindevops"
RUN echo "Trainer is: ${TRAINER}, version is: ${version}"
CMD [ "sleep", "200" ]