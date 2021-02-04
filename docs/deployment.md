# Deployment Guide

## Run the operator locally

`OPERATOR_NAME=gitops-operator operator-sdk run local --watch-namespace=""`

**Note:** Please check that you're using [operator-sdk]( https://github.com/operator-framework/operator-sdk/releases/tag/v0.17.2) version 0.17 or earlier. Since the community-operators do not support `v1` version of `CustomResourceDefinition`, the operator is using `v1beta1` version of `CustomResourceDefinition`.


## Operator Lifecycle Manager


## Manual Installation


