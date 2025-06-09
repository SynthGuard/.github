# SynthGuard

**Scalable, Secure, and Modular Synthetic Data Workflows**

**SynthGuard** is a cloud-native, modular system for building and managing privacy-preserving synthetic data workflows at scale. Designed with GDPR compliance, reproducibility, and extensibility in mind, SynthGuard empowers researchers and developers to automate complex data synthesis pipelines using modern container orchestration and workflow tools.

---

## 🔍 About the Project

Synthetic data enables safe data sharing in regulated domains such as healthcare and finance. However, generating high-quality synthetic datasets that meet privacy and utility goals is non-trivial. SynthGuard addresses this by offering:

- A **Kubernetes-native workflow framework** for synthetic data generation.
- A **Python library** for data preprocessing, synthesis, evaluation, and privacy risk assessment.
- A scalable, reproducible, and privacy-aware approach suitable for both academic and industrial applications.

SynthGuard has been developed and validated in real-world EU-funded projects.

---

## 🧱 Project Structure

This organization hosts two core repositories:

### [`synthguard-framework`](https://github.com/SynthGuard/synthguard-framework)

A complete orchestration framework to define, deploy, and manage synthetic data generation workflows.

**Features:**

- ⚙️ Modular pipeline automation with configuration-driven notebook generation.
- ☁️ Integration with **Kubeflow Pipelines** for scalable execution.
- 🐳 Containerized with Docker and deployable using Nix & Minikube.

➡️ **[View Framework Documentation »](https://github.com/SynthGuard/synthguard-framework/blob/main/README.md)**

---

### [`synthguard-library`](https://github.com/SynthGuard/synthguard-library)

A Python library providing core functionalities for preprocessing, synthetic data generation, data quality evaluation, and privacy risk analysis.

**Features:**

- 🔄 Data preprocessing and metadata extraction.
- 🧪 Synthetic data generation using multiple strategies (e.g., realistic, hybrid).
- 📊 Data quality assessment with SDV metrics and visualization.
- 🔐 Privacy risk evaluation (identimages emoji ity & attribute disclosure).
- 🧰 Utility functions for data handling, validation, and logging.

➡️ **[View Library Documentation »](https://github.com/SynthGuard/synthguard-library/blob/main/README.md)**

---

## 🏛 Acknowledgements

### EXAI
<img src="./EXAI-logo-eng.png" alt="EXAI Logo" height="50" />

> The EXAI (Estonian Centre of Excellence in AI) project is funded by the Estonian Ministry of Education and Research.

### TEADAL  
<img src="https://teadal.eu/wp-content/uploads/sites/84/2022/08/TEADAL_rgb_logo_extended.png" alt="TEADAL Logo" height="50" />

<img src="https://european-union.europa.eu/themes/contrib/oe_theme/dist/eu/images/logo/standard-version/positive/logo-eu--en.svg" alt="EU Logo" height="50" >

> The TEADAL (Trustworthy, Energy-Aware federated DAta Lakes along the computing continuum) project is funded by the EU’s Horizon Europe program under Grant Agreement number 101070186. Views and opinions expressed are those of the author(s) only and do not necessarily reflect those of the European Union. Neither the European Union nor the granting authority can be held responsible for them. This work also received funding from the Swiss State Secretariat for Education, Research and Innovation (SERI).

### LAGO  
<img src="https://lago-europe.eu/themes/custom/lago_theme/lago_theme/logo.svg" alt="LAGO Logo" height="50" />

<img src="https://european-union.europa.eu/themes/contrib/oe_theme/dist/eu/images/logo/standard-version/positive/logo-eu--en.svg" alt="EU Logo" height="50" >

> The LAGO ("Lessen Data Access and Governance Obstacles") project is funded by the EU's Horizon Europe program under Grant Agreement number 101073951. Views and opinions expressed are those of the author(s) only and do not necessarily reflect those of the European Union or the European Research Executive Agency. Neither the European Union nor the granting authority can be held responsible for them.

## 🗃️ Assets

🖼️ **[View SynthGuard Logos »](https://github.com/SynthGuard/.github/assets)**

## 📄 License

This project is licensed under the terms specified in the license file.  
📜 **[View License »](https://github.com/SynthGuard/synthguard-library/blob/main/LICENSE.md)**
