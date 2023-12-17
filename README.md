
# `k8s-argocd-aws`

## Overview

This repository contains a set of Terraform modules and scripts to deploy an ArgoCD instance on AWS.

## Prerequisites

- [Terraform](https://www.terraform.io/downloads.html) >= 0.12.0
- [kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/) >= 1.14.0
- [aws-iam-authenticator](https://docs.aws.amazon.com/eks/latest/userguide/install-aws-iam-authenticator.html) >= 0.4.0
- [awscli](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html) >= 1.16.0
- [helm](https://helm.sh/docs/using_helm/#installing-helm) >= 2.14.0
- [jq](https://stedolan.github.io/jq/download/) >= 1.6

## Usage

### Deploy ArgoCD
