FROM jenkins/jenkins:lts-slim

USER root

RUN curl -sSL https://get.docker.com/ | sh

RUN usermod -aG staff jenkins

USER jenkins
