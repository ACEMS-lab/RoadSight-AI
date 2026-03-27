# RoadSight AI

RoadSight AI is a multimodal edge AI framework for real time traffic video search, incident detection, and cross camera situational awareness in intelligent transportation systems. The project transforms roadway camera networks into searchable, incident aware operational infrastructure by integrating three tightly coupled capabilities:

1. **Search**  
   Natural language retrieval over live or archived traffic video streams.

2. **Detection**  
   Motion aware identification of evolving roadway disruptions such as stopped vehicles, debris, wrong way driving, abnormal slowdowns, and emerging congestion.

3. **Tracing**  
   Cross camera association of vehicles, queues, and incidents to preserve event continuity and generate multi camera timelines.

The system is designed as a cloud to edge workflow using NVIDIA enabled model development, optimization, and deployment pathways, with the goal of reducing operator burden, accelerating incident discovery, and improving traffic safety monitoring. :contentReference[oaicite:3]{index=3} :contentReference[oaicite:4]{index=4}

---

## Why this project matters

Traffic agencies operate large camera networks, but incident detection and verification are still largely manual and reactive. Existing traffic monitoring tools often rely on fixed event logic, manual CCTV review, and limited cross camera continuity. RoadSight AI addresses this gap by adding a software intelligence layer to existing roadway camera infrastructure, enabling operators to search, detect, and trace traffic events more efficiently without requiring large scale hardware replacement. :contentReference[oaicite:5]{index=5}

---

## Core innovation

RoadSight AI introduces a unified framework that combines:

- **Semantic video search** for static and operator defined events using natural language queries
- **Motion based incident understanding** for dynamic behaviors and emerging disruptions
- **Cross camera tracing** for continuous spatiotemporal understanding across adjacent views

This combination moves traffic operations from passive monitoring to proactive, searchable, incident aware intelligence. :contentReference[oaicite:6]{index=6}

---

## Repository scope

This repository is intended to host the project codebase, metadata definitions, sample annotations, dataset utilities, and release documentation for permitted components of RoadSight AI. Depending on data sharing permissions, this repository may include:

- released code for perception, retrieval, and evaluation
- selected sample clips or images
- processed outputs such as trajectories or event labels
- metadata and label schema definitions
- scripts for download, verification, preprocessing, and frame extraction
- documentation for dataset usage and release notes

The main dataset includes multi camera traffic video, image frames, text queries, event labels, object tracks, and scene metadata. The project plan indicates a combination of in house traffic camera data and selected open source traffic video datasets, with any shared subset to be de identified where required. :contentReference[oaicite:7]{index=7}

---
**Dataset Access:** [SharePoint Repository](https://panthers-my.sharepoint.com/:f:/g/personal/xion2268_uwm_edu/IgAGl56s5IHnRJKlmstSMrnHAQ96hCybPLNlE8zOQU4WyI4?e=hvahhL)

```text
project-dataset/
├─ README.md
├─ LICENSE
├─ CITATION.cff
├─ metadata/
│  ├─ camera_list.csv
│  ├─ dataset_manifest.csv
│  ├─ checksums.sha256
│  └─ label_schema.json
├─ annotations/
│  ├─ sample_annotations.csv
│  └─ format_description.md
├─ samples/
│  ├─ sample_images/
│  └─ sample_clips/
├─ scripts/
│  ├─ download_dataset.py
│  ├─ verify_checksums.py
│  └─ extract_frames.py
└─ docs/
   └─ usage_and_release_notes.md
