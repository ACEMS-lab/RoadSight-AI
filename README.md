# RoadSight AI

**RoadSight AI** is a multimodal edge AI framework for real time traffic video search, incident detection, and cross camera situational awareness in intelligent transportation systems. The project is designed to help traffic agencies transform existing roadway camera networks into searchable, intelligent, and operationally useful infrastructure for faster incident awareness and response.

The system integrates three tightly coupled capabilities:

- **Search**  
  Natural language retrieval of relevant live or archived traffic video.

- **Detection**  
  Motion aware identification of roadway disruptions such as stopped vehicles, wrong way driving, debris, abnormal slowdowns, and emerging congestion.

- **Tracing**  
  Cross camera continuity of vehicles, queues, and incidents to support network level situational awareness.

---

## Project Motivation

Traffic agencies operate extensive roadway camera networks, yet incident detection and verification often remain manual and reactive. This delays awareness of crashes, debris, wrong way driving, stopped vehicles, and congestion forming across adjacent locations. RoadSight AI addresses this gap by introducing a unified multimodal edge AI framework that enables operators to search traffic video, detect evolving events, and trace incidents across cameras in real time.

This project is intended to support safer, faster, and more scalable traffic operations without requiring full replacement of existing camera infrastructure.

---

## Core Innovation

RoadSight AI advances the current state of practice by combining three functions in a single operational framework:

1. **Semantic Search**  
   Retrieves relevant traffic video using natural language queries over live or archived streams.

2. **Incident Detection**  
   Uses motion aware analysis to identify evolving disruptions and operationally relevant events.

3. **Cross Camera Tracing**  
   Maintains continuity of vehicles, queues, and incidents across adjacent camera views.

Together, these capabilities move traffic monitoring from passive viewing to active, searchable, and context aware operational intelligence.

---

## Key Features

- Real time and archived traffic video search
- Natural language query interface for traffic operators
- Motion based roadway event detection
- Cross camera object and incident continuity
- Multimodal cloud to edge AI workflow
- Support for intelligent transportation system monitoring and situational awareness
- Dataset organization for metadata, annotations, samples, and release documentation

---

## Dataset Access

The RoadSight AI dataset and related project files are hosted on SharePoint and can be accessed here:

**Dataset repository:**  
[RoadSight AI Dataset on SharePoint](https://panthers-my.sharepoint.com/:f:/g/personal/xion2268_uwm_edu/IgAGl56s5IHnRJKlmstSMrnHAQ96hCybPLNlE8zOQU4WyI4?e=hvahhL)

Access may be restricted to authorized collaborators depending on project permissions and data sharing policies.

---
The dataset follows a simple structure consisting of traffic video files and their corresponding annotation files. The current demo release includes one sample video clip and one corrected XML annotation file, and this structure will be expanded with additional clips, labels, and metadata in later stages of the project.
## Repository Structure
dataset/
├─ video/
│  └─ 5m_demo.mp4
├─ annotation/
│  └─ corrected_gt_5m_demo.xml
└─ README.md
