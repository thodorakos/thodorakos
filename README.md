# Theodoros Nikaris

**DevOps & Backend Development**

Open to junior DevOps and backend development opportunities.

[LinkedIn](https://www.linkedin.com/in/thodoris-nikaris-a8708b277/) · [Email](mailto:thodoris.nikaris@gmail.com)

I build containerized services and Kubernetes projects, focusing on reproducible
deployments, service networking, and validation scripts that check actual behavior.
My backend work uses Java with Spring Boot and Python with FastAPI.

## DevOps projects

### [Go Microservices on Kubernetes](https://github.com/thodorakos/k8s-go-microservices)

Two Go services packaged with multi-stage Docker builds and a Helm chart.
Includes service discovery, health probes, and an optional canary routing demo.

### [FastAPI Autoscaling](https://github.com/thodorakos/k8s-fastapi-autoscaling)

CPU-based Kubernetes autoscaling for a FastAPI service. A load generator and
validation script check scaling up under load and returning to one replica.

### [Cilium Network Policies](https://github.com/thodorakos/k8s-cilium-network-policies)

Default-deny networking for a three-tier demo, with explicit service and DNS rules,
kubelet probe handling, and scripted checks for allowed and blocked traffic.

### [Kubernetes Operators & Automation](https://github.com/thodorakos/Assignments_HY-548_csd4965)

Kubernetes extension lab with Python CRD controllers and an admission webhook,
plus Helm deployment, ingress, and horizontal pod autoscaling.

## Backend projects

### [AEGIS — Natural Disaster Monitor](https://github.com/thodorakos/aegis)

FastAPI service that ingests NASA EONET events into PostgreSQL/PostGIS, flags
events in Greece, and exposes filtering and summary APIs. Docker Compose runs
the API, database, and React interface together.

### [Private Dining — Reservation System](https://github.com/thodorakos/private_dining)

Spring Boot API with JWT authentication, booking validation, and protected
administration endpoints. PostgreSQL persistence, a React client, and Docker
Compose for local setup.

## Core tools

- **Infrastructure:** Linux, Docker, Docker Compose, Kubernetes, Helm, Cilium
- **Automation:** Git, GitHub Actions, Bash
- **Backend:** Java, Spring Boot, Python, FastAPI, PostgreSQL, PostGIS
