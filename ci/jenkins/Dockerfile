FROM jenkinsci/blueocean:1.4.2

RUN apt-get update && apt-get install -y --no-install-recommends usermod

RUN usermod -aG docker $USER

RUN ssh-keygen
