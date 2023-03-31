# Argo Rollouts plugin

This is a [StackSpot](https://docs.stackspot.com) plugin, based on CDK, that adds an [Argo Rollouts's Manifest](https://argoproj.github.io/argo-rollouts/features/specification/) to make available to the application the option of using a canary deployment.

# How to use

Go to application folder and type:

```
stk apply plugin zup-kotlin-stack/argorollouts-app-kt-plugin
```

# Prerequisites

This plugin is applicable in applications that were created from the template [https://github.com/stack-spot/spring-app-kt-template](https://github.com/stack-spot/spring-app-kt-template).

