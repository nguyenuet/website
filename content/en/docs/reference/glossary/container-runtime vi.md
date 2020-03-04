---
title: Container Runtime
id: container-runtime
date: 2020-03-04
full_link: /docs/reference/generated/container-runtime
short_description: >
 The container runtime is the software that is responsible for running containers.
 Container runtime là một phần mềm cái mà chịu trách nhiệm để chạy các container.
aka:
tags:
- fundamental
- workload
---
 The container runtime is the software that is responsible for running containers.
 Container runtime là một phần mềm cái mà chịu trách nhiệm để chạy các container.
<!--more-->

Kubernetes supports several container runtimes: {{< glossary_tooltip term_id="docker">}},
{{< glossary_tooltip term_id="containerd" >}}, {{< glossary_tooltip term_id="cri-o" >}},
and any implementation of the [Kubernetes CRI (Container Runtime 
Interface)](https://github.com/kubernetes/community/blob/master/contributors/devel/sig-node/container-runtime-interface.md).
Kubernetes hỗ trợ một vài container runtime: {{< glossary_tooltip term_id="docker">}}, {{< glossary_tooltip term_id="containerd" >}}, {{< glossary_tooltip term_id="cri-o" >}}, và bất kỳ thực thi nào của [Kubernetes CRI (Container Runtime Interface)](https://github.com/kubernetes/community/blob/master/contributors/devel/sig-node/container-runtime-interface.md).