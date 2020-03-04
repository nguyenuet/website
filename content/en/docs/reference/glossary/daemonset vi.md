---
title: DaemonSet
id: daemonset
date: 2018-04-12
full_link: /docs/concepts/workloads/controllers/daemonset
short_description: >
  Ensures a copy of a Pod is running across a set of nodes in a cluster.
  Đảm bảo một bản sao của Pod đang chạy trên một tập các node của cluster.
aka: 
tags:
- fundamental
- core-object
- workload
---
 Ensures a copy of a {{< glossary_tooltip text="Pod" term_id="pod" >}} is running across a set of nodes in a {{< glossary_tooltip text="cluster" term_id="cluster" >}}.
 Đảm bảo một bản sao của {{< glossary_tooltip text="Pod" term_id="pod" >}} đang chạy trên một tập các node của {{< glossary_tooltip text="cluster" term_id="cluster" >}}.

<!--more--> 

Used to deploy system daemons such as log collectors and monitoring agents that typically must run on every {{< glossary_tooltip term_id="node" >}}.
Được sử dụng để deploy những system daemon ví dụ như log collector, monitoring agent, những cái thường phải chạy trên mỗi {{< glossary_tooltip term_id="node" >}}.

