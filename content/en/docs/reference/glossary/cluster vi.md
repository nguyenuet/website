---
title: Cluster
id: cluster
date: 2020-02-26
full_link: 
short_description: >
   A set of worker machines, called nodes, that run containerized applications. Every cluster has at least one worker node.
   Một tập các worker machine, được gọi là node, dùng để chạy các containerized application. Mỗi cụm (cluster) có ít nhất một worker node.

aka: 
tags:
- fundamental
- operation
---
A set of worker machines, called nodes, that run containerized applications. Every cluster has at least one worker node.
Một tập các worker machine, được gọi là node, dùng để chạy các containerized application. Mỗi cụm (cluster) có ít nhất một worker node.

<!--more-->
The worker node(s) host the pods that are the components of the application. The Control Plane manages the worker nodes and the pods in the cluster. In production environments, the Control Plane usually runs across multiple computers and a cluster usually runs multiple nodes, providing fault-tolerance and high availability.
Các worker node chứa các pod, trong đó pod là thành phần của ứng dụng. Control Plane quản lý những worker node và pod trong cluster. Trong môi trường sản phẩm (production environment), Control Plane luôn chạy trên nhiều máy tính và một cluster luôn nhạy trên nhiều nodes, cung cấp khả năng chịu lỗi (fault-tolerance) và tính sẵn sàng cao (high availability)