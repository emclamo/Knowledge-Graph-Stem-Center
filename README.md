# Knowledge Graph: STEM Research Center Best Practices

This project visualizes ten best practices developed over five years by a STEM research center. The graph highlights three strategic objectives—**Recruit**, **Retain**, and **Engage**—and shows how practices relate through directional, weighted connections and thematic clusters.

![Knowledge Graph Banner](assets/repo-banner.png)

---

## 🎯 Objectives

- **Recruit Broadly**
- **Retain and Reward Participants**
- **Engage Faculty, Students, and Community**
- **Assess and Calibrate Continuously**

Each practice is represented as a node, color-coded by cluster. Arrows reflect directional influence and are labeled with qualitative relationships (e.g., _supports_, _informs_, _reinforces_).

---

## 📂 Included Files

| File                                | Description                                       |
|-------------------------------------|---------------------------------------------------|
| `graph_generator.py`                | Main script to generate the knowledge graph       |
| `layout_positions.pkl`              | Stored layout for reproducibility                 |
| `knowledge_graph_with_text.png`     | Graph with labeled nodes and directional edges    |
| `knowledge_graph_no_labels.png`     | Clean version for overlays or presentations       |
| `assets/repo-banner.png`            | GitHub social preview/banner image                |
| `requirements.txt`                  | Python packages required for script               |

---

## 🚀 How to Run

Install dependencies:

```bash
pip install networkx matplotlib

