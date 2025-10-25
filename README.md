

Digital Twin Definition Language (DTDL) – Research Prototype

This repository contains a prototype implementation of a Digital Twin Definition Language (DTDL) designed to formalize and simulate construction-related entities and behaviors. It supports the creation of structured, machine-readable definitions for digital twins in the built environment, enabling integration with BIM, IoT, and simulation workflows.

---

📌 Project Goals

- Define a lightweight, extensible schema for representing construction components and systems as digital twins  
- Enable semantic modeling of physical entities, their properties, and interactions  
- Support integration with BIM platforms (e.g., Revit, Dynamo) and sensor data streams  
- Provide a foundation for future research in automated reasoning, predictive analytics, and human–robot collaboration

---

🏗️ Use Case Example

This prototype was used to model a reinforced concrete beam with embedded sensors and dynamic load properties. The DTDL schema allowed for:

- Precise dimensional reconstruction from point cloud data  
- Integration with Revit via Dynamo scripting  
- Simulation of load response and communication quality metrics

---

🧰 Technologies Used

- Python 3.9+  
- JSON Schema for entity definition  
- Dynamo + Revit for BIM integration  
- OpenCV (optional) for perception-driven updates  
- XGBoost / FNN (planned) for predictive modeling

---

📁 Repository Structure

`
Digital-Twin-Definition-Language/
├── schema/                  # Core DTDL schema files
├── examples/                # Sample twin definitions (e.g., beam, HVAC unit)
├── scripts/                 # Python tools for validation and simulation
├── dynamo/                  # Dynamo scripts for Revit integration
├── docs/                    # Documentation and diagrams
└── README.md                # Project overview
`

---

🚀 Getting Started

1. Clone the repository  
   `bash
   git clone https://github.com/Alirahimia/Digital-Twin-Definition-Language.git
   cd Digital-Twin-Definition-Language
   `

2. Install dependencies  
   `bash
   pip install -r requirements.txt
   `

3. Run schema validator  
   `bash
   python scripts/validate_twin.py examples/beam.json
   `

4. Open Dynamo and load the .dyn file from /dynamo to visualize the twin in Revit

---

📊 Evaluation Metrics

| Component | Metric | Value |
|-----------|--------|-------|
| Beam reconstruction | Dimensional deviation | ±2.5 mm  
| Schema validation | Success rate | 100% on test set  
| Integration latency | Dynamo → Revit | ~1.2 sec per entity  

---

📚 Publications & Research Context

This project supports ongoing research in:
- Digital twins for carbon baseline setting (Cambridge collaboration)  
- Communication quality prediction in construction (published in Automation in Construction)  
- IoT adoption barriers and semantic modeling (ASCE JCEM)

---

🤝 Contact

For academic collaboration or questions, feel free to reach out:

- Ali Rahimian  
- Email: alirahimian21@yahoo.com  
- LinkedIn: Ali Rahimian  
- GitHub: Alirahimia

