---
# Removed from Kubernetes
title: RotateKubeletClientCertificate
content_type: feature_gate

_build:
  list: never
  render: false

stages:
  - stage: beta 
    defaultValue: true
    fromVersion: "1.8"
    toVersion: "1.18"
  - stage: stable
    defaultValue: true
    fromVersion: "1.19"
    toVersion: "1.21"

removed: true
---

<!--
Enable the rotation of the client TLS certificate on the kubelet.
See [kubelet configuration](/docs/reference/access-authn-authz/kubelet-tls-bootstrapping/#kubelet-configuration)
for more details.
-->
启用 kubelet 上客户端 TLS 证书的轮换。
更多细节参阅 [kubelet 配置](/zh-cn/docs/reference/access-authn-authz/kubelet-tls-bootstrapping/#kubelet-configuration)。
