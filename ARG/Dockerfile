ARG version
FROM almalinux:${version:-9}
ENV course="Devops with AWS"\
    trainer="siva kumar"\
    duration="120HRS"
#Here username is key, some_user is default value.
ARG USERNAME=Balaguru
ENV USERNAME=$USERNAME
RUN echo "Hello User: ${USERNAME}, image version:${version}" > /tmp/devops.txt
CMD [ "sleep", "200" ]