---
title: Controller
id: controller
date: 2020-03-04
full_link: /docs/concepts/architecture/controller/
short_description: >
  A control loop that watches the shared state of the cluster through the apiserver and makes changes attempting to move the current state towards the desired state.
  Một vòng lặp điều khiển (control loop), dùng để quan sát các trạng thái được chia sẻ trong cluster thông qua apiserver và cố gắng để chuyển từ trạng thái hiện tại sang trạng thái mong đợi.

aka: 
tags:
- architecture
- fundamental
---
In Kubernetes, controllers are control loops that watch the state of your
{{< glossary_tooltip term_id="cluster" text="cluster">}}, then make or request
changes where needed.
Each controller tries to move the current cluster state closer to the desired
state.
Trong Kubernetes, các controller là các vòng lặp điều khiển (control loop), dùng để quan sát các trạng thái được chia sẻ trong {{< glossary_tooltip term_id="cluster" text="cluster">}} của bạn, sau đó thực hiện hoặc yêu cầu những thay đổi cần thiết.
Mỗi controller cố gắng để chuyển trạng thái hiện tại gần hơn với trạng thái mong đợi.  

<!--more-->

Controllers watch the shared state of your cluster through the
{{< glossary_tooltip text="apiserver" term_id="kube-apiserver" >}} (part of the
{{< glossary_tooltip term_id="control-plane" >}}).
Các controller quan sát trạng thái được chia sẻ trong cluster của bạn thông qua {{< glossary_tooltip text="apiserver" term_id="kube-apiserver" >}} (một phần của {{< glossary_tooltip term_id="control-plane" >}}).

Some controllers also run inside the control plane, providing control loops that
are core to Kubernetes' operations. For example: the deployment controller, the
daemonset controller, the namespace controller, and the persistent volume
controller (and others) all run within the
{{< glossary_tooltip term_id="kube-controller-manager" >}}.
Một vài controller cũng chạy bên trong control plane, cung cấp những vòng lặp điều khiển cái mà là một hoạt động chính trong Kubernetes. Ví dụ: tất cả deployment controller, daemonset controller, namespace controller, và persistent volume controller (và khác) đều chạy bên trong {{< glossary_tooltip term_id="kube-controller-manager" >}}.
