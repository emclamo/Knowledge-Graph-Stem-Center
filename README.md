# Knowledge-Graph-Stem-Center
Map and visualize best practices in STEM research centers using a color-coded, directed knowledge graph
markdown
CopyEdit
# Knowledge Graph: STEM Research Center Best Practices

This repository contains a Python-based tool to visualize best practices in a STEM research center using a structured knowledge graph. The graph highlights thematic clusters, weighted relationships, and feedback mechanisms across key activities like recruitment, retention, engagement, and assessment.

## 🎯 Objectives

The graph maps ten evidence-based best practices developed over five years of research into three strategic objectives:
- **Recruit Broadly**
- **Retain and Reward Participants**
- **Engage Faculty, Students, and Community**

Each cluster is color-coded, and relationships are labeled and weighted to reflect influence and feedback.

## 🗂 Files

- `graph_generator.py`: Main Python script to generate and save the graphs.
- `knowledge_graph_with_text.png`: Labeled graph with full node and edge annotations.
- `knowledge_graph_no_labels.png`: Clean version for overlay or design use.
- `layout_positions.pkl`: Stores a fixed graph layout for consistent outputs.

## 📦 Requirements

```bash
pip install networkx matplotlib
![image](https://github.com/user-attachments/assets/86aafe11-755c-459e-b42b-014b09625435)

🚀 How to Run
bash
CopyEdit
python graph_generator.py
This will generate two PNGs (with and without labels) using a stable layout saved in layout_positions.pkl.

🧠 Highlights
•	Uses networkx for directed graph creation
•	Visualizes weights, edge labels, and thematic clusters
•	Includes a clean legend with flexible layout and color coding
•	Designed for reproducibility and clarity
![image](https://github.com/user-attachments/assets/355ad70b-6c27-4f60-8f9e-d535da13d2f8)
