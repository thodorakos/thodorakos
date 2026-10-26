<p>
  <img src="https://raw.githubusercontent.com/thodorakos/thodorakos/main/assets/header.svg?v=navy-green-2" width="1000" height="208" alt="Theodoros Nikaris: DevOps & backend development" />
</p>

[<img src="https://raw.githubusercontent.com/thodorakos/thodorakos/main/assets/linkedin.svg?v=navy-green-2" width="132" height="44" alt="LinkedIn" />](https://www.linkedin.com/in/thodoris-nikaris-a8708b277/) &nbsp; [<img src="https://raw.githubusercontent.com/thodorakos/thodorakos/main/assets/email.svg?v=navy-green-2" width="132" height="44" alt="Email" />](mailto:thodoris.nikaris@gmail.com)

I'm looking for a **junior DevOps role** and am also interested in backend development.

I build containerized services and work with Kubernetes. My projects focus on
repeatable deployments and service networking, with validation scripts to check
that the services behave as expected. For backend work, I use Java with Spring
Boot and Python with FastAPI.

*Each project runs locally, and its README shows the setup steps and how to verify the result.*

## <img src="https://raw.githubusercontent.com/thodorakos/thodorakos/main/assets/infrastructure.svg?v=navy-green-2" width="20" height="20" alt="" /> DevOps projects

[**Go microservices on Kubernetes**](https://github.com/thodorakos/k8s-go-microservices)<br>
A Helm chart deploys two Go services built with multi-stage Dockerfiles and
includes service discovery, health probes, an optional canary routing demo,
and Prometheus and Grafana. The validation script checks both the routing
and the metrics.

[**FastAPI autoscaling**](https://github.com/thodorakos/k8s-fastapi-autoscaling)<br>
Kubernetes scales a FastAPI service based on CPU usage. A load generator
drives the test, the validation script checks that the service scales to
four replicas and back to one, and Prometheus and Grafana record the
metrics during the test.

[**Cilium network policies**](https://github.com/thodorakos/k8s-cilium-network-policies)<br>
Cilium enforces default-deny networking for a three-tier demo. The policies
explicitly allow service and DNS traffic and account for kubelet probes.
A validation script checks which connections are allowed or blocked.

[**Kubernetes operators & automation**](https://github.com/thodorakos/Assignments_HY-548_csd4965)<br>
This Kubernetes lab has Python CRD controllers and an admission webhook.
It also includes Helm deployment, ingress, and horizontal pod autoscaling.

## <img src="https://raw.githubusercontent.com/thodorakos/thodorakos/main/assets/backend.svg?v=navy-green-2" width="20" height="20" alt="" /> Backend projects

[**AEGIS: Natural disaster monitor**](https://github.com/thodorakos/aegis)<br>
AEGIS ingests NASA EONET events into PostgreSQL/PostGIS and flags events in
Greece. Its FastAPI backend provides filtering and summary APIs. Docker Compose
runs the API, database, and React interface together.

[**Private Dining: Reservation system**](https://github.com/thodorakos/private_dining)<br>
The reservation system has a Spring Boot API and a PostgreSQL database.
The API uses JWT authentication, validates bookings, and protects administration
endpoints. Docker Compose runs the backend and React client for local use.

## Tools

| Area | Tools |
| :--- | :--- |
| Infrastructure | Linux · Docker · Docker Compose · Kubernetes · Helm · Cilium · Prometheus · Grafana |
| Automation | Git · GitHub Actions · Bash |
| Backend | Java · Spring Boot · Python · FastAPI · PostgreSQL · PostGIS |
