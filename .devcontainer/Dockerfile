FROM registry.access.redhat.com/ubi9/nodejs-20:1

USER root

RUN mkdir /opt/workspace && \
# Install yarn
  curl --silent --location https://dl.yarnpkg.com/rpm/yarn.repo | tee /etc/yum.repos.d/yarn.repo && \
  dnf install yarn -y

USER default
