<img width="1441" height="302" alt="banner" src="https://github.com/user-attachments/assets/3bdb3f31-4b9d-478d-b119-a48d86421170" />
<h1>Hi there , I am Ann</h1>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=F7B00F&width=700&lines=Builder+Over+Researcher;MLOps+%2F+Deep+Learning+Engineer;Spring+Backend;TS+%2F+Node.js+;Cloud+Automation+and+Platform+Eng.;AWS+%E2%80%A2+Docker+%E2%80%A2+K8s+%E2%80%A2+CI%2FCD+%E2%80%A2+Prometheus+%26+Grafana;Hard-coding+Latte)](https://git.io/typing-svg)

---

<h2> 👨🏻‍💻 &nbsp;A Little Bit About Me and My Interests</h2>

```yaml
name: Ann
current_status: Engineering Student & MLOps Builder
target_roles: ["MLOps Engineer Intern", "Backend / AI Systems Engineer"]

education:
  - "B.Tech in AI & Data Science" 

fields_of_interests:
  - "Machine Learning Operations (MLOps)"
  - "High-Performance Model Serving"
  - "Distributed System Architecture"
  - "Enterprise Backend Engineering"
  - "Cloud Automation & Platform Engineering"

technical_background:
  - "Full-Stack Development (Spring Boot, Node.js, TS, Postgres)"
  - "Deep Learning Implementation (PyTorch, Model Training)"
  - "DevOps / Infrastructure Engineering (AWS, CI/CD, Docker)"

currently_learning: 
  - "NVIDIA Triton Inference Server (Production Model Serving)"
  - "Model Compilation & Optimization (TensorRT, ONNX)"
  - "Cluster Orchestration & Telemetry (Kubernetes, Prometheus, Grafana)"

2026_Goals: 
  - "Bridge the gap between academic AI models and production enterprise infrastructure."
  - "Build and ship open-source, end-to-end MLOps deployment pipelines."

hobbies: ["Gaming", "Bowling", "System Crafting"]
```

![Snake animation](https://github.com/finna-ann/finna-ann/blob/output/github-contribution-grid-snake-dark.svg)

---
<h2 id="target-architecture">🏗️ Target System Architecture — MLOps Pipeline</h2>

<p>This is the architecture I'm building toward: a Spring Boot / Node.js API gateway bridging into a GPU-accelerated inference layer, with full observability. Current status of each piece is noted below the diagram.</p>

```text
[ Client Request ] ──► [ API Gateway ] ───( gRPC — planned )───► [ Inference Server ]
                            │                                          │
                 ( Spring Boot / Node.js )                    ( PyTorch Engine / ONNX )
                            │                                          │
                            ▼                                          ▼
               [ PostgreSQL Database ]                    [ Prometheus & Grafana ]
                 ( User & Session State )                  ( Cluster & Telemetry )
```

<ul>
  <li>📦 <b>Orchestration Layer (planned):</b> target is a Docker-isolated multi-container setup, deployed onto Kubernetes (EKS) once the gateway and serving layers are wired together.</li>
  <li>⚡ <b>Low-Latency Pipeline (planned):</b> intend to replace REST with gRPC streams between the gateway and inference server — currently still an open design decision, not implemented.</li>
  <li>📊 <b>Observability:</b> built early test instrumentation with Prometheus/Grafana — not yet wired into a full pipeline, but the groundwork is in place.</li>
  <li>🧠 <b>Inference layer (evaluating):</b> still deciding on the serving engine — looking at Triton.</li>
</ul>

---

<h2> 🚀 &nbsp;Tools, Frameworks, and Infrastructure</h2>

<!-- 🤖 AI & MLOps Infrastructure -->
<h3>&nbsp;&nbsp;🤖 AI & MLOps Engine</h3>
<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="python" width="45" height="45"/>&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" alt="pytorch" width="45" height="45"/>&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" alt="fastapi" width="45" height="45"/>&nbsp;&nbsp;
  <img src="https://www.edge-ai-vision.com/wp-content/uploads/2018/10/mlogo.png" alt="onnx" width="45" height="45"/>&nbsp;&nbsp;
  <img src="https://www.svgrepo.com/show/331511/nvidia.svg" alt="triton" width="45" height="45"/>
</p>

<!-- ☁️ Cloud & Platform Engineering -->
<h3>&nbsp;&nbsp;☁️ Cloud & DevOps Platform</h3>
<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" alt="docker" width="45" height="45"/>&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-original.svg" alt="kubernetes" width="45" height="45"/>&nbsp;&nbsp;
   <img src="https://www.svgrepo.com/show/331300/aws.svg" alt="aws" width="45" height="45"/>&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/prometheus/prometheus-original.svg" alt="prometheus" width="45" height="45"/>&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/grafana/grafana-original.svg" alt="grafana" width="45" height="45"/>&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" alt="linux" width="45" height="45"/>&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" alt="bash" width="45" height="45"/>
</p>

<!-- 💻 Backend & Core Engineering -->
<h3>&nbsp;&nbsp;💻 Enterprise Backend & Data</h3>
<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="java" width="45" height="45"/>&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" alt="spring" width="45" height="45"/>&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" alt="typescript" width="45" height="45"/>&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" alt="nodejs" width="45" height="45"/>&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/grpc/grpc-original.svg" alt="grpc/google" width="45" height="45"/>&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" alt="postgresql" width="45" height="45"/>&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="git" width="45" height="45"/>
</p>

---

<h2>📫 &nbsp;Let's Connect and Build</h2>
<p align="left">
  <!-- 💼 LinkedIn Connection Button -->
  <a href="https://www.linkedin.com/in/marine-a-02728042a/" target="_blank">
    <img src="https://www.svgrepo.com/show/157006/linkedin.svg" alt="LinkedIn" width="45" height="45"/>
  </a>&nbsp;&nbsp;

  <!-- 🐦 X (Twitter) Connection Button -->
  <a href="https://x.com/_marine_ann" target="_blank">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSDIBc9BXghz1Wjh1N1F5LJ7VFuElkO7U4BLoTUJSljkASMtZvY3wFjzbYl&s=10" alt="X / Twitter" width="45" height="45"/>
  </a>
</p>


