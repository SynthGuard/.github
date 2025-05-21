# SynthGuard

**Scalable, Secure, and Modular Synthetic Data Workflows**

**SynthGuard** is a cloud-native, modular system for building and managing privacy-preserving synthetic data workflows at scale. Designed with GDPR compliance, reproducibility, and extensibility in mind, SynthGuard empowers researchers and developers to automate complex data synthesis pipelines using modern container orchestration and workflow tools.

---

## 🔍 About the Project

Synthetic data enables safe data sharing in regulated domains, such as healthcare and finance. However, generating high-quality synthetic datasets that meet privacy and utility goals is non-trivial. SynthGuard addresses this by offering:

- A **Kubernetes-native workflow framework** for synthetic data generation.
- A **Python library** for data preprocessing, synthesis, evaluation, and privacy risk assessment.
- A scalable, reproducible, and privacy-aware approach suitable for both academic and industrial applications.

SynthGuard has been developed and validated in real-world EU-funded projects.

---

## 🧱 Project Structure

This organization hosts two core repositories:

### [`synthguard-framework`](https://github.com/your-org/synthguard-framework)

A complete orchestration framework to define, deploy, and manage synthetic data generation workflows.

**Features:**

- ⚙️ Modular pipeline automation with configuration-driven notebook generation.
- ☁️ Integration with **Kubeflow Pipelines** for scalable execution.
- 🐳 Containerized with Docker and deployable using Nix & Minikube.

➡️ [View Framework Documentation]([https://github.com/your-org/synthguard-framework](https://github.com/SynthGuard/synthguard-framework))

---

### [`synthguard-library`](https://github.com/your-org/synthguard-library)

A Python library providing core functionalities for preprocessing, synthetic data generation, data quality evaluation, and privacy risk analysis.

**Features:**

- 🔄 Data preprocessing and metadata extraction.
- 🧪 Synthetic data generation using multiple strategies (e.g., realistic, hybrid).
- 📊 Data quality assessment with SDV metrics and visualization.
- 🔐 Privacy risk evaluation (identity & attribute disclosure).
- 🧰 Utility functions for data handling, validation, and logging.

➡️ [View Library Documentation]([https://github.com/your-org/synthguard-library](https://github.com/SynthGuard/synthguard-library))

## 📄 License

This project is licensed. 
📄 [View License](https://github.com/SynthGuard/synthguard-library/blob/main/LICENSE.md)
