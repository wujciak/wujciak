# Hi, I'm Jakub Wójciak

<p align="left">
  <a href="https://www.linkedin.com/in/jwojciak/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</p>

ML Engineer based in Olsztyn, Poland, working remotely (open to relocating to Wrocław or Łódź). I train models, check that their evaluation holds up, and build
the backend that serves them. Most of my work is in medical data and speech.

- **ML Engineer at EENGINE Software House.** Speech recognition for call-center audio: fine-tuned
  Whisper for Polish (WER from 16% to 12%) and NeMo FastConformer for Romanian (WER from 30% to
  17%), plus LLM-based extraction from call transcripts.
- **Backend developer at Oncosort** (finalist of *Our Future Founders*). Spring Cloud
  microservices for a medical data platform.
- **MSc Computer Engineering** (2026) and **BEng Biomedical Engineering**, medical informatics
  (2025), Wrocław University of Science and Technology.

## Selected projects

**Machine learning**

- [**medical-ood-detection**](https://github.com/wujciak/medical-ood-detection). My master's
  thesis: label-free out-of-distribution detection from K-Means centroid distances on frozen ViT
  and ResNet-50 embeddings. It covers 80 configurations, each with 5-fold cross-validation and
  Friedman–Nemenyi tests. AUROC is 0.999 on far-OOD and 0.81 on near-OOD, and the CNN beats
  the ViT on near-OOD.
- [**thyroid-ultrasound-vit**](https://github.com/wujciak/thyroid-ultrasound-vit). My engineering
  thesis, redone after I found data leakage in the original evaluation. A pretrained ViT-B/16
  reaches 0.75 AUROC per patient on 157 held-out patients. It also includes shortcut tests,
  Grad-CAM and a FastAPI + React demo.
- [**pcb-yolo**](https://github.com/wujciak/pcb-yolo). PCB defect detection with a Canny edge map
  fused into the input channels of YOLO11n, which raises mAP@0.5:0.95 on DeepPCB from 0.742 to
  0.765. It is written up as an IEEE-format paper.
- [**ecg-arrhythmia-classification**](https://github.com/wujciak/ecg-arrhythmia-classification).
  Heartbeat classification on MIT-BIH into the AAMI classes. The same CNN-LSTM scores 0.93
  macro-F1 when beats are split at random, as in my first version, and 0.47 on unseen patients.

**Software engineering**

- [**cvrp-metaheuristics**](https://github.com/wujciak/cvrp-metaheuristics). A genetic algorithm,
  simulated annealing and baselines for vehicle routing, in plain Java. The genetic algorithm
  gets within 4.7% of the optimum on the Augerat A-set.
- [**library-management-system**](https://github.com/wujciak/library-management-system). A Spring
  Boot REST API with JWT and role-based access, Liquibase migrations, row locking and 19
  Testcontainers integration tests. It has a React UI, Docker Compose and CI.

## Tech stack

**Machine learning**

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" title="Python" alt="Python" height="40" />&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" title="PyTorch" alt="PyTorch" height="40" />&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg" title="TensorFlow" alt="TensorFlow" height="40" />&nbsp;&nbsp;
  <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" title="scikit-learn" alt="scikit-learn" height="40" />&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" title="NumPy" alt="NumPy" height="40" />&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" title="pandas" alt="pandas" height="40" />
</p>

**Backend**

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" title="Java" alt="Java" height="40" />&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" title="Spring Boot" alt="Spring Boot" height="40" />&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" title="FastAPI" alt="FastAPI" height="40" />&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" title="PostgreSQL" alt="PostgreSQL" height="40" />&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" title="MySQL" alt="MySQL" height="40" />&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" title="Docker" alt="Docker" height="40" />&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" title="Linux" alt="Linux" height="40" />
</p>

**Frontend**

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" title="TypeScript" alt="TypeScript" height="40" />&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" title="React" alt="React" height="40" />&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" title="Next.js" alt="Next.js" height="40" />
</p>
