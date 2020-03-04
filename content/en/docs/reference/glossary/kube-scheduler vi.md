---
title: kube-scheduler
id: kube-scheduler
date: 2018-04-12
full_link: /docs/reference/generated/kube-scheduler/
short_description: >
  Control Plane component that watches for newly created pods with no assigned node, and selects a node for them to run on.
  Thành phần của Control Plane, được dùng để giám sát việc tạo những pod mới mà chưa có node được chỉ định, và chọn một node để chúng chạy trên đó.

aka: 
tags:
- architecture
---
 Control Plane component that watches for newly created pods with no assigned node, and selects a node for them to run on.
 Thành phần của Control Plane, được dùng để giám sát việc tạo những pod mới mà chưa có node được chỉ định, và chọn một node để chúng chạy trên đó.

<!--more--> 

Factors taken into account for scheduling decisions include individual and collective resource requirements, hardware/software/policy constraints, affinity and anti-affinity specifications, data locality, inter-workload interference and deadlines.
Những yếu tố trong những quyết định lập lịch bao gồm những yêu cầu về tài nguyên, những đòi hỏi về phần cứng/phần mềm/chính sách, những thông số về affinity và anti-affinity, dữ liệu tại chỗ, nhiễu inter-workload và thời hạn.
