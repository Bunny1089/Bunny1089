<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorStart=3a0ca3&customColorEnd=7209b7&height=200&section=header&text=MEET&fontSize=50&fontColor=ffffff" width="100%" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=9D4EDD&center=true&vCenter=true&width=500&lines=Distributed+Systems+Architect;AI+/+ML+Platform+Engineer;Full+Stack+Product+Engineer;Open+Source+Contributor" alt="Typing SVG" />
</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/MS%20in%20Computer%20Science-Georgia%20Tech-7B2CBF?style=flat-square&logo=academia&logoColor=white" alt="Academic Badge" /></a>
  <a href="#"><img src="https://img.shields.io/badge/Location-San%20Francisco%2C%20CA-5A189A?style=flat-square&logo=googlemaps&logoColor=white" alt="Location" /></a>
  <a href="https://portfolio.dev"><img src="https://img.shields.io/badge/Portfolio-website-9D4EDD?style=flat-square&logo=react&logoColor=white" alt="Portfolio" /></a>
  <a href="https://linkedin.com/in/username"><img src="https://img.shields.io/badge/LinkedIn-profile-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:email@example.com"><img src="https://img.shields.io/badge/Email-contact-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/username"><img src="https://img.shields.io/badge/GitHub-profile-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>
</p>

<p align="center">
  <a href="#"><img src="https://komarev.com/ghpvc/?username=username&color=9D4EDD&style=flat-square&label=Profile%20Views" alt="Profile Views" /></a>
  <a href="https://github.com/username"><img src="https://img.shields.io/github/followers/username?style=flat-square&color=7B2CBF&label=Followers" alt="Followers" /></a>
  <a href="https://github.com/username"><img src="https://img.shields.io/github/stars/username?style=flat-square&color=7B2CBF&label=Stars" alt="Stars" /></a>
</p>

---

## 2. About Me

I am a Senior Software Engineer specializing in high-performance distributed systems, AI/ML training and inference infrastructure, and scalable full-stack applications. With a product engineering mindset, I bridge the gap between complex backend infrastructure and intuitive user experiences. I thrive on designing robust solutions that handle millions of requests, optimizing GPU utilization, and contributing to open-source software.

*   **Software Engineering:** Expert in microservices, low-latency APIs, and concurrent system designs.
*   **AI/ML Expertise:** Specialized in pipeline parallelism, LLM fine-tuning pipelines, and vector databases.
*   **Full Stack Development:** Experienced in building responsive, modern user interfaces integrated with resilient backend APIs.
*   **Product Mindset:** Focused on delivering measurable business impact, optimizing cost, and ensuring excellent user experience.

### Open To
*   Technical leadership roles and architecture advisory.
*   Collaborations on open-source distributed training frameworks and ML developer tools.
*   System optimization and scalability consulting.

---

## 3. Tech Stack

### Languages
[![Languages](https://skillicons.dev/icons?i=python,js,ts,golang,rust,cpp)](https://skillicons.dev)

### Frontend
[![Frontend](https://skillicons.dev/icons?i=react,nextjs,html,css,sass,tailwind)](https://skillicons.dev)

### Backend & Databases
[![Backend](https://skillicons.dev/icons?i=nodejs,express,graphql,postgres,mongodb,redis)](https://skillicons.dev)

### Cloud, DevOps & Tooling
[![Cloud & DevOps](https://skillicons.dev/icons?i=aws,gcp,docker,kubernetes,git,linux)](https://skillicons.dev)

---

## 4. AI / ML Expertise

| Domain | Proficiency | Details |
| :--- | :--- | :--- |
| **Deep Learning Infrastructure** | Expert | PyTorch, Megatron-LM, DeepSpeed, Ray, GPU cluster orchestration, CUDA kernel tuning |
| **NLP & Large Language Models** | Advanced | Fine-tuning (LoRA, QLoRA), Reinforcement Learning (RLHF/DPO), RAG architectures |
| **Computer Vision** | Advanced | Object detection (YOLO), image segmentation, OpenCV, multi-modal feature embedding |
| **MLOps & Inference Platforms** | Expert | Triton Inference Server, vLLM, TensorRT, Kubeflow, Prometheus, Grafana |

---

## 5. Featured Projects

<details>
<summary><b>🚀 AetherDB — Distributed Serverless Vector Database</b></summary>

### AetherDB
A high-throughput, low-latency serverless vector database designed specifically for real-time semantic search and high-dimensional embeddings.

| Stack | Scale | Performance | Security | Impact | Repository |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Go, Rust, gRPC, Kubernetes, RAFT | 50B+ Vectors, multi-region | <5ms latency at 99th percentile | TLS 1.3, OAuth2, RBAC | Powering semantic search for 10M+ DAUs | [aether-db](https://github.com/username/aether-db) |

#### Professional Project Explanation
AetherDB was built to solve the memory and indexing bottlenecks of high-dimensional vector search. The core vector indexing search engine is built in Rust utilizing custom HNSW algorithms, while the orchestration and distributed replication layers are written in Go. Raft consensus ensures consistent and partition-tolerant cluster coordination. Implemented dynamic vector quantization and memory-mapped files to optimize memory consumption, reducing infrastructure costs by 50%.
</details>

<details>
<summary><b>🧠 NeuralMesh — Distributed LLM Orchestration Platform</b></summary>

### NeuralMesh
A cloud-native orchestration platform designed to streamline large-scale model training and inference workloads across heterogeneous GPU clusters.

| Stack | Scale | Performance | Security | Impact | Repository |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Python, PyTorch, Ray, Docker, Slurm | 1000+ GPU nodes, 175B model | 92% GPU utilization efficiency | End-to-end data encryption, VPC | Reduced model training cost by 40% | [neural-mesh](https://github.com/username/neural-mesh) |

#### Professional Project Explanation
NeuralMesh abstracts cluster-level GPU complexities for machine learning teams. Built on top of Ray and Kubernetes, it automatically partitions models using pipeline, tensor, and data parallelism. By incorporating predictive scheduling algorithms, it dynamically detects and routes around failing compute nodes, ensuring uninterrupted, long-running training jobs. Optimized networking throughput with custom NCCL communication topologies over InfiniBand fabrics.
</details>

<details>
<summary><b>⚡ VortexPay — Ultra-Low Latency Payment Gateway</b></summary>

### VortexPay
A high-frequency transactional gateway designed for microtransactions, processing thousands of requests per second with sub-millisecond persistence.

| Stack | Scale | Performance | Security | Impact | Repository |
| :--- | :--- | :--- | :--- | :--- | :--- |
| C++, Rust, PostgreSQL, Redis, Kafka | 10,000+ RPS, $100M+ Volume | Sub-10ms end-to-end latency | PCI-DSS compliant, HSM integration | 99.999% uptime, zero financial leakage | [vortex-pay](https://github.com/username/vortex-pay) |

#### Professional Project Explanation
VortexPay leverages C++ for its main execution pipeline and Rust for its critical external-facing validation modules to guarantee performance without sacrificing memory safety. It maintains a transactional ledger with high durability using a custom log-structured write-ahead log (WAL). Employs memory-mapped databases and lock-free rings to achieve high throughput, handling peaks of up to 15,000 requests per second under heavy loads.
</details>

---

## 6. Professional Experience

### **Staff Software Engineer / Tech Lead** | **Meta**
*August 2023 - Present*
*   **Description:** Lead the architecture team designing infrastructure for next-generation generative AI features across consumer applications.
*   **Scope of Work:**
    *   Designed and deployed a distributed caching system for model weights, reducing start-up times for inference pods by 65%.
    *   Architected a cross-region data replication pipeline processing multi-terabyte datasets daily with zero loss.
    *   Mentored senior engineers, defined long-term technical roadmaps, and established rigorous code review standards.
*   **Skills:** `Distributed Systems` `PyTorch` `C++` `Kubernetes` `System Design`

### **Senior Software Engineer** | **Google**
*June 2020 - August 2023*
*   **Description:** Developed key features and optimization engines for core search backend indexing services.
*   **Scope of Work:**
    *   Led the refactoring of legacy indexing pipelines, increasing index construction throughput by 30% using Go.
    *   Designed real-time health-checks and anomaly detection telemetry suites, preventing critical downstream indexing delays.
    *   Collaborated closely with machine learning researchers to deploy custom retrieval models into live serving environments.
*   **Skills:** `Go` `C++` `TensorFlow` `GCP` `Microservices`

---

## 7. Achievements

<p align="center">
  <table>
    <thead>
      <tr>
        <th style="text-align: left;">Recognition</th>
        <th style="text-align: left;">Details</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>🏆 **FAANG Engineering Excellence Award**</td>
        <td>Recognized for optimizing core service latency, reducing global system resource footprint by 20%.</td>
      </tr>
      <tr>
        <td>🌟 **Open Source Contributor of the Year**</td>
        <td>Acknowledged for significant contributions to PyTorch compiler frontends and distributed training packages.</td>
      </tr>
      <tr>
        <td>🥇 **1st Place — Global AI Hackathon**</td>
        <td>Developed a prototype multi-agent code refactoring tool capable of automated modular conversions.</td>
      </tr>
    </tbody>
  </table>
</p>

---

## 8. Certifications

### AWS
<p align="left">
  <a href="#"><img src="https://img.shields.io/badge/AWS-Solutions%20Architect%20Professional-480CA8?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS SA Pro" /></a>
  <a href="#"><img src="https://img.shields.io/badge/AWS-Security%20Specialty-560BAD?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS Security" /></a>
</p>

### Oracle
<p align="left">
  <a href="#"><img src="https://img.shields.io/badge/Oracle-Java%20SE%2011%20Professional-7209B7?style=flat-square&logo=oracle&logoColor=white" alt="Oracle Java SE 11" /></a>
</p>

### NPTEL
<p align="left">
  <a href="#"><img src="https://img.shields.io/badge/NPTEL-Cloud%20Computing%20(Elite%2BGold)-3F37C9?style=flat-square&logo=education&logoColor=white" alt="NPTEL Cloud Computing" /></a>
  <a href="#"><img src="https://img.shields.io/badge/NPTEL-Advanced%20Algorithms-4361EE?style=flat-square&logo=education&logoColor=white" alt="NPTEL Advanced Algorithms" /></a>
</p>

### Cisco
<p align="left">
  <a href="#"><img src="https://img.shields.io/badge/Cisco-CCNA-4CC9F0?style=flat-square&logo=cisco&logoColor=white" alt="Cisco CCNA" /></a>
</p>

---

## 9. Coding Profiles

<p align="center">
  <a href="https://leetcode.com/username"><img src="https://img.shields.io/badge/LeetCode-Profile-7B2CBF?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode" /></a>
  <a href="https://geeksforgeeks.org/user/username"><img src="https://img.shields.io/badge/GeeksforGeeks-Profile-5A189A?style=for-the-badge&logo=geeksforgeeks&logoColor=white" alt="GeeksforGeeks" /></a>
  <a href="https://hackerrank.com/username"><img src="https://img.shields.io/badge/HackerRank-Profile-9D4EDD?style=for-the-badge&logo=hackerrank&logoColor=white" alt="HackerRank" /></a>
  <a href="https://codechef.com/users/username"><img src="https://img.shields.io/badge/CodeChef-Profile-E0AAFF?style=for-the-badge&logo=codechef&logoColor=black" alt="CodeChef" /></a>
</p>

---

## 10. GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=username&show_icons=true&title_color=9d4edd&icon_color=7b2cbf&text_color=e0aaff&bg_color=0d0c15&hide_border=true&count_private=true" alt="GitHub Stats" width="48%" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=username&theme=tokyonight&background=0d0c15&ring=7b2cbf&fire=9d4edd&currStreakNum=e0aaff&sideNums=e0aaff&sideLabels=e0aaff&dates=e0aaff&hide_border=true" alt="Streak Stats" width="48%" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=username&layout=compact&title_color=9d4edd&icon_color=7b2cbf&text_color=e0aaff&bg_color=0d0c15&hide_border=true" alt="Top Languages" width="60%" />
</p>

---

## 11. GitHub Trophies

<p align="center">
  <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=username&theme=dracula&column=7&no-bg=true" alt="GitHub Trophies" /></a>
</p>

---

## 12. Contribution Activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=username&bg_color=0d0c15&color=9d4edd&line=7b2cbf&point=e0aaff&area=true&hide_border=true" alt="Contribution Graph" width="100%" />
</p>

---

## 13. Contribution Snake

<p align="center">
  <img src="https://raw.githubusercontent.com/username/username/output/github-contribution-grid-snake-dark.svg" alt="Snake Grid" width="100%" />
</p>

---

## 14. Current Focus

```yaml
current_focus:
  learning:
    - "Advanced Distributed Consensus Algorithms"
    - "Geometric Deep Learning & Graph Neural Networks"
  building:
    - "An open-source high-performance vector index engine in Rust"
    - "A developer tool for optimizing CUDA kernel performance"
  exploring:
    - "Post-Quantum Cryptography implementations in distributed ledgers"
    - "Mechanistic Interpretability of Large Language Models"
  open_to:
    - "Collaborating on cutting-edge open-source AI infra"
    - "Advising early-stage tech startups on system architecture"
```

---

## 15. Connect with Me

<p align="center">
  <a href="mailto:email@example.com"><img src="https://img.shields.io/badge/Gmail-7209B7?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" /></a>
  <a href="https://linkedin.com/in/username"><img src="https://img.shields.io/badge/LinkedIn-3F37C9?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://github.com/username"><img src="https://img.shields.io/badge/GitHub-480CA8?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://portfolio.dev"><img src="https://img.shields.io/badge/Portfolio-560BAD?style=for-the-badge&logo=react&logoColor=white" alt="Portfolio" /></a>
</p>

---

<p align="center">
  <i>"First, solve the problem. Then, write the code." — John Johnson</i>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorStart=7209b7&customColorEnd=3a0ca3&height=100&section=footer" width="100%" />
</p>
