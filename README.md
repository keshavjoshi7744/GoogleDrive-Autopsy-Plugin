# Google Drive Sync Artifact Parser for Autopsy

### MSc Cyber Security Dissertation – University of York (2025)  
**Author:** Keshav Joshi  
**Supervisor:** Dr. Angus Marshall  
**Project Type:** Digital Forensics Research and Tool Development   

---

## 📘 Overview

This repository contains the practical and research work completed as part of my **MSc Cyber Security dissertation** at the **University of York**.  
The project involved designing and developing a **custom Autopsy ingest module** that automates the parsing and analysis of **Google Drive for Desktop (DriveFS)** artifacts used in digital forensic investigations.

These artifacts include:
- `metadata_sqlite.db`  
- `mirror_metadata.db`  
- `structured_log_global`  
- `LocalPrefs.json`  

The tool integrates with Autopsy to automatically extract, analyse, and correlate evidence for **timeline reconstruction** and **cloud file activity analysis**, helping investigators work faster and with better accuracy.

---

## 💡 Motivation

As more evidence now resides in cloud storage platforms, understanding local DriveFS artifacts has become essential for digital forensics.  
The project aimed to **bridge a gap in existing open-source tools** by automating DriveFS analysis — reducing manual effort and improving consistency across investigations.

---

## 🧩 Design and Implementation

The project combined two main stages:

1. **Artifact Exploration:**  
   DriveFS data structures were examined manually using FTK Imager and SQLite DB Browser to understand metadata and logs.  
2. **Plugin Development:**  
   A Python (Jython) plugin was created using the **Autopsy Ingest API**, which extracts and displays DriveFS data in Autopsy’s blackboard for timeline and evidence correlation.

This approach ensured both **theoretical understanding** and **practical software delivery**, meeting a common challenge in forensic research projects.

---

## 🧪 Evaluation

The module was tested using multiple sets of DriveFS artifacts under controlled forensic conditions.  
Results showed:
- **Up to 90% reduction in manual analysis time**  
- **Accurate reconstruction of file and user activity timelines**  
- **Integrity verification through hashing**  

While overall results were strong, feedback highlighted that **some sections of analysis could be structured more systematically**, and **screenshots and figures** could be clearer or better attributed, improvements planned for a future release.

---

## 🧠 Technical Stack

- **Languages:** Python / Jython  
- **Framework:** Autopsy Ingest API (Sleuth Kit)  
- **Tools:** Autopsy, FTK Imager, DB Browser for SQLite  
- **Test Environment:** Windows 10 VM with Google Drive for Desktop (v88+)  
- **Artifact Formats:** SQLite, JSON, Log  

---

## 🔍 Key Features

- Automated parsing of DriveFS artifacts (SQLite, JSON, Logs)  
- Timeline generation for user activity  
- Evidence correlation and integrity checks  
- Integration into Autopsy’s blackboard for visualisation  
- Modular Python (Jython) design for easy updates  

---

## 📊 Limitations and Future Work

- Improve figure clarity and proper attribution in documentation  
- Add structured evaluation for reproducibility  
- Extend the plugin to support additional DriveFS versions and cloud API integration  

---

---

## ⚖️ License

This project is distributed under the **MIT License**.  
See the [LICENSE](./LICENSE) file for details.

---

## 🧾 Citation

If referencing this work, please cite as:

> Joshi, K. (2025). *Google Drive Sync Artifact Parser for Autopsy*. MSc Dissertation, University of York.

---

## 📬 Contact

**Keshav Joshi**  
📧 [keshav.infinity8@gmail.com](mailto:keshav.infinity8@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/keshavjoshi28)  
💻 [GitHub](https://github.com/keshavjoshi7744)

---

## 🟢 Summary

This project demonstrates end-to-end development of a forensic analysis tool, from manual artifact study to full Autopsy integration.  
It highlights skills in **Python automation, digital forensics, cloud artifact analysis and secure software development**, with practical results that align closely with real-world investigations.

While there’s room for refinement in reporting and visualisation, the project showcases strong technical execution and a clear understanding of both **research and applied cybersecurity** ,the qualities I bring to every professional role.



