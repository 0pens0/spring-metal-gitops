# Demo of Tanzu platform Gitops with Github

![Tanzu](https://img.shields.io/badge/tanzu-platform-purple.svg)
![Tanzu platform gitops](https://github.com/0pens0/spring-metal-gitops/actions/workflows/gitops.yml/badge.svg)

This repository contains artifacts necessary to run Gitops loop based on Github actions for Tanzu Platform.

## Architecture

![Alt text](https://github.com/0pens0/spring-metal-gitops/blob/master/image.png?raw=true "Spring-metal AI topology")

## Prerequisites
- Ensure you have access to Tanzu platform for K8s
- Confiogure the paratemers under the repo settings

Get in to secrets and vars configuration in the repository level >> https://github.com/0pens0/spring-metal-gitops/settings/secrets/actions and configure the following:

TPK8S parameters:

- API_ENDPOINT = the api end point information >> api.tanzu.cloud.vmware.com
- API_TOKEN = tanzu api token to connect to TPK8S service

