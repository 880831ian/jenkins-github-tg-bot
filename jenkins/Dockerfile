FROM jenkins/jenkins:lts-jdk11

LABEL maintainer="880831ian@gmail.com"

USER root

RUN apt-get upgrade -y\
    && apt-get update -y\
    && apt-get install yamllint -y