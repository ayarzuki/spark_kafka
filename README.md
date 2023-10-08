# Dibimbing, Data Engineering Bootcamp

## Task
### 1. Menggunakan complete mode file berada dalam spark-scripts/task-dibimbing-consume.py
### 2. Mencoba menggunakan update mode file berada dalam spark-scripts/sum.py

## How to run scripts
1. Clone This Repo.
2. Run `make docker-build` for x86 user, or `make docker-build-arm` for arm chip user.

---
```
## docker-build			- Build Docker Images (amd64) including its inter-container network.
## docker-build-arm		- Build Docker Images (arm64) including its inter-container network.
## postgres			- Run a Postgres container
## spark			- Run a Spark cluster, rebuild the postgres container, then create the destination tables
## jupyter			- Spinup jupyter notebook for testing and validation purposes.
## airflow			- Spinup airflow scheduler and webserver.
## clean			- Cleanup all running containers related to the challenge.
```

---
