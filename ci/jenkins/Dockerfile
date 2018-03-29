FROM jenkins/jenkins:lts-slim

RUN ssh-keygen -f ~/.ssh/id_rsa -t rsa -N ''

USER root

RUN curl -sSL https://get.docker.com/ | sh

USER jenkins
