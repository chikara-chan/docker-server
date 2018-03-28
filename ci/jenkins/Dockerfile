FROM jenkins/jenkins:lts-slim

USER root

RUN curl -sSL https://get.docker.com/ | sh

USER jenkins

RUN ssh-keygen -f ~/.ssh/id_rsa -t rsa -N ''
