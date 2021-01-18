# FrameworkPerformanceComparison

Here we are comparing performances of CRUD operatins of web services build using micronaut and spring boot. Both services are identical in terms of functinality. We are usign jmeter to perform load testing. Services are deployed in container managed by docker and orchestration is handled by kubernetes(minikube). We are using prometheous and grafana for visualizing the CPU and Memory consumption.

Environment details:
1. Java Version: 1.8(OpenJdk Alpine)
2. Kubernetes
3. CPU: 1
4. Memory: Request 1G
           Limit 2G
