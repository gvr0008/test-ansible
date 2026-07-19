FROM quay.io/ansible/creator-ee:latest

USER root

RUN ansible-galaxy collection install infra.aap_configuration

WORKDIR /workspaces/test-ansible

COPY . /workspaces/test-ansible

USER 1000
