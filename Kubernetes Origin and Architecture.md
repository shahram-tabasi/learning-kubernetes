History: Google, Omega and Bourge since 2014. merge them as kubernetes, open source software for deploy and managing of containers.

============================

Kubernetes big picture

App Descriptor   ->  manifest (requirements) 

Kubernetes Master  

Kubernetes cloud  ->  set of introduces servers  -> workers

====================================

Control Plane(Master)  -> ETCD, API Server, Scheduler, Controller Manager

Data Plane(worker)  ->   Kubelet, Container Runtime, Kube Proxy

=====================================

Kubelet  ->  connection bridge between worker and master

container Runtime  -> pull image from repository

Kube Proxy  -> connection to Api server

===========================================
Admin user, use kubectl to work with cluster
