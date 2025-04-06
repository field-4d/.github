# FIELD-4D: A Phenotyping Framework for Advanced Agricultural Research

<div >
<img src="https://avatars.githubusercontent.com/u/71197432?s=400&u=837258e8d4c3b42fe4d44789e3602a3d83b64b61&v=4" alt="F4D Logo" width="230" height="240"> 
 <img src="https://docs.contiki-ng.org/en/master/_static/contiki_logo.png" alt="Contiki-NG Logo" width="256"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d0/Yellow_ribbon.svg/200px-Yellow_ribbon.svg.png" alt="Yellow Ribbon Logo" width="80">
</div>


---

**FIELD-4D** is a modular and extensible **research framework** developed over several years in the **Moshelion Lab** at the Hebrew University of Jerusalem. It is designed to support **real-time outdoor phenotyping**, combining physiological modeling, sensor networks, and scalable cloud infrastructure.

> This repository serves as the central hub of the FIELD-4D ecosystem and integrates three specialized submodules:
> 
> - 📡 **IoT** — environmental sensing, edge computing, and WSN.
> - ☁️ **Cloud** — cloud infrastructure, storage, and APIs.
> - 🧬 **Sci-PHY** — scientific modeling of plant physiology, physics, and phenotypes.

---

## 📁 Repository Structure

```
FIELD-4D/
├── IoT/         # Sensor nodes, data acquisition, field hardware
├── Cloud/       # Cloud integration, APIs, and data pipelines
└── Sci-PHY/     # Physiology models, data analysis, and visualization
```

Each sub-repository is version-controlled independently and contributes to the broader FIELD-4D platform.

---

## 🌟 Highlights

- **Physiological Research-Backed**: Built on years of empirical research and field testing.
- **Flexible & Modular**: Supports multiple sensors, cloud platforms, and data types.
- **Scalable Design**: Adaptable from small-scale trials to full-field installations.
- **Bridging Science and Deployment**: Combines physics, plant science, and engineering.
- **Academic Collaboration Ready**: Designed for research partners, not just developers.

---

## 🔌 Submodules Overview

### 📡 IoT Model (`/IoT`)

Handles field-level data capture and processing:

- Wireless Sensor Network (WSN) protocols
- Power-efficient edge computation
- Real-time measurements: temp, humidity, radiation, VPD, etc.
- [🔗 View IoT Details »](./IoT)

---

### ☁️ Cloud Model (`/Cloud`)

Manages cloud infrastructure and data services:

- Google Cloud integration: BigQuery, Firebase, Cloud Run
- RESTful API endpoints for internal and external apps
- CI/CD, infrastructure as code (Terraform), monitoring
- Data pipelines for real-time and batch processing

[🔗 View Cloud Details »](./Cloud)

---

### 🧬 Sci-PHY Model (`/Sci-PHY`)

Scientific and physiological engine of the framework:

- Crop growth modeling, stress response simulation
- Light interception, heat balance, and transpiration modeling
- Data science tools for CSV, JSON, and NetCDF formats
- **This module may be released as open source** for community collaboration

[🔗 View Sci-PHY Details »](./Sci-PHY)

---

## 🛠️ Technologies Used

- **Languages**: Python, C/C++, Bash
- **Frameworks**: Docker, Terraform, GitHub Actions
- **Cloud**: Google Cloud Platform (BigQuery, Pub/Sub, Firebase)
- **Monitoring**: Prometheus, Grafana, InfluxDB
- **Scientific Tools**: Pandas, NumPy, Matplotlib, SciPy

---

## 🎯 Use Cases

- Outdoor phenotyping and physiological experimentation
- Remote crop monitoring and precision irrigation systems
- Integration with drones, imaging, and remote sensing tools
- Field-ready deployments with research-grade validation

---

## 🤝 Collaboration

We are open to **scientific collaborations**, pilot projects, and institutional partnerships. FIELD-4D is a **branded framework**—not a public open-source platform. Access and contributions are curated and reviewed based on relevance to our research goals.

---

## 🔖 License & Access

FIELD-4D is a **proprietary academic research framework**.  
The `Sci-PHY` module may be shared under an open license upon request or release.

---

## 🧠 Developed By

**The Moshelion Lab**  
Robert H. Smith Faculty of Agriculture, Food and Environment  
The Hebrew University of Jerusalem, Rehovot, Israel

- **Idan Ifrach**, Hebrew University of Jerusalem Israel | [idan.ifrachi@mail.huji.ac.il](mailto:idan.ifrachi@mail.huji.ac.il) | [GitHub](https://github.com/ifrachi) | [LinkedIn](https://www.linkedin.com/in/ifrachi/) | [ORCID](https://orcid.org/0009-0000-0552-0935)

- **Nir Averbuch**, PhD Student, Hebrew University of Jerusalem Israel [averbuch.nir@gmail.com](mailto:averbuch.nir@gmail.com) | [GitHub](https://github.com/averbuchnir)

- **Prof. Menachem Moshelion**, Hebrew University of Jerusalem, Israel [menachem.moshelion@mail.huji.ac.il](mailto:menachem.moshelion@mail.huji.ac.il) | [LinkedIn](https://il.linkedin.com/in/menachem-moshelion-45aa689a) | [ORCID](https://orcid.org/0000-0003-0156-2884)

---

## 📬 Contact

For institutional inquiries or collaboration opportunities:

**📧 Email:**   greenroom.lab@mail.huji.ac.il
**📍 Location:** Rehovot, Israel

---

---

> *FIELD-4D bridges the complexity of plant science with the power of modern technology.*
