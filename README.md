# Kubernetes Developer Learning Path

Course: https://redhatquickcourses.github.io/k8s-dev-lmp/

## Overview

This course provides a comprehensive overview of the Kubernetes architecture and its powerful extensibility mechanisms. We will start by learning how the Kubernetes API functions behind the scenes, exploring how cluster requests are authenticated, authorized, and validated by the control plane. The core of the course focuses on platform automation, teaching you how to extend Kubernetes by defining custom resources and writing custom controllers or operators to automatically manage different workloads. To ensure these extensions are robust, we will also cover essential distributed system principles required to build these highly available components and safely handle concurrent updates. Finally, the course explores advanced networking and traffic management concepts while broadening the focus into essential cluster-wide concerns, teaching us how to harden your environments alongside an exploration of alternative control plane architectures like HyperShift and kcp.

## Who is this for?

This course is tailor-made for engineers, sys admins, developers who already possess some experience running and managing container workloads within Kubernetes environments.
Additionally, a basic primer on distributed systems is highly recommended to easily grasp the complex concurrency, leasing, and synchronization mechanics covered in the modules.
Ideally, readers should have a baseline equivalent to holding a CKAD (Certified Kubernetes Application Developer) certification or having completed Red Hat's DO-180 and DO-280 tracks.

## Modules

- **Week 0** — Familiarizing with koo·br·neh·teez
- **Week 1.1** — Kubernetes Resource Model
- **Week 1.2** — Controllers, informers, client-go
- **Week 2.1** — Controllers contd. (controller-runtime, kubebuilder)
- **Week 2.2** — Going distributed: locks, leases, ownership, eventual consistency
- **Week 3.1** — Taking more control: Admissions and beyond the kube-apiserver
- **Week 3.2** — The other stuff (Networking, Service Mesh, Security)
- **Week 4.1** — All about kube-scheduler
- **Week 4.2** — Ubiquitous topics! (HyperShift, kcp, microshift, k3s)

## Recommended Reading

- *Programming Kubernetes: Developing Cloud-Native Applications* — Hausenblas, Michael, and Stefan Schimanski (O'Reilly Media, 2019)
- *Kubernetes Operators: Automating the Container Orchestration Platform* — Dobies, Jason, and Joshua Wood (O'Reilly Media, 2020)
- CNCF Operator Whitepaper: https://tag-app-delivery.cncf.io/whitepapers/operator/
