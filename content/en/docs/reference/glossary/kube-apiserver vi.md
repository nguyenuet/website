---
title: API server
id: kube-apiserver
date: 2020-02-26
full_link: /docs/reference/generated/kube-apiserver/
short_description: >
  Control plane component that serves the Kubernetes API.
  Thành phần tầng điểu khiển (control plane), được dùng để phục vụ Kubernetes API.

aka:
- kube-apiserver
tags:
- architecture
- fundamental
---
 The API server is a component of the Kubernetes
{{< glossary_tooltip text="control plane" term_id="control-plane" >}} that exposes the Kubernetes API.
The API server is the front end for the Kubernetes control plane.
 API server là một thành phần của Kubernetes {{< glossary_tooltip text="control plane" term_id="control-plane" >}}, được dùng để đưa ra Kubernetes API.
API server là front end của Kubernetes control plane.

<!--more-->

The main implementation of a Kubernetes API server is [kube-apiserver](/docs/reference/generated/kube-apiserver/).
kube-apiserver is designed to scale horizontally&mdash;that is, it scales by deploying more instances.
You can run several instances of kube-apiserver and balance traffic between those instances.
Thực thi chính của API server là [kube-apiserver](/docs/reference/generated/kube-apiserver/).
kube-apiserver được thiết kế để co giãn theo chiều ngang&mdash; có nghĩa là nó co giãn bằng cách triển khai thêm các thực thể.
Bạn có thể chạy một vài thực thể của kube-apiserver và cân bằng lưu lượng giữa các thực thể này.