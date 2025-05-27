FROM almalinux:9
ENV course="Devops with AWS"\
    trainer="siva kumar"\
    duration="120HRS"
#Here username is key, some_user is default value. and we override as well. if we won't give any value it will take default value
ARG ${username:-some_user}
RUN echo "Hello ${username}" > /tmp/devops.txt
CMD [ "sleep", "200" ]