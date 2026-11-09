# 🐳 Dockerfiles Playground

A collection of Dockerfiles created while learning and experimenting with Docker and containerization.

This repository contains different Dockerfiles for building, configuring, and running applications using Docker. It serves as a personal collection of hands-on experiments, practice exercises, and implementation examples.

## 📂 Repository Contents

Dockerfiles for different technologies and use cases, including:

- Python applications
- Node.js applications
- Java applications
- Nginx web servers
- Custom Docker images
- Multi-stage builds
- Alpine-based images
- Production-ready container configurations

## 🛠️ Concepts Practiced

- Dockerfile instructions (`FROM`, `RUN`, `COPY`, `ADD`, `WORKDIR`)
- Environment variables (`ENV`)
- Port configuration (`EXPOSE`)
- Container startup commands (`CMD`, `ENTRYPOINT`)
- Image optimization
- Multi-stage builds
- Non-root user configuration
- Dependency management
- Docker image layering and caching

## 🚀 Build and Run

Build an image using a Dockerfile:

```bash
docker build -t my-image -f Dockerfile .
```

Build using a custom-named Dockerfile:

```bash
docker build -t my-image -f node-dockerfile .
```

Run the container:

```bash
docker run -d --name my-container my-image
```

View available images:

```bash
docker images
```

View running containers:

```bash
docker ps
```

## 🎯 Purpose

- Practise writing Dockerfiles from scratch.
- Experiment with different base images.
- Understand Docker build processes.
- Explore image optimization techniques.
- Test different container configurations.
- Learn through practical implementation and troubleshooting.

## 📌 Repository Status

This is an ongoing collection. New Dockerfiles and experiments will be added as I explore more Docker concepts.

---

**Author:** Infant Joseph

**Technologies:** Docker | Linux | Containerization | DevOps

