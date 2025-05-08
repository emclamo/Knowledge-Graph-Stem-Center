# Knowledge Graph: STEM Research Center Best Practices

This project visualizes ten best practices developed over five years by a STEM research center. The graph highlights three strategic objectives—**Recruit**, **Retain**, and **Engage**—and shows how practices relate through directional, weighted connections and thematic clusters.

![Knowledge Graph Banner](Banner%20Image.png)


---

## ✨ Highlights

- 🎯 Visualizes 10 evidence-based STEM center best practices  
- 🧭 Shows directional relationships and feedback loops  
- 🎨 Color-coded thematic clusters for clarity  
- 🧩 Includes both labeled and clean PNG exports  
- 💾 Stores a fixed layout for reproducible graph positioning  
- 🔁 Easy to adapt for other institutional strategies or centers  

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
| `graph_generator.py`                | Python script used to generate the knowledge graph |
| `layout_positions.pkl`              | Stored layout to ensure consistent output         |
| `knowledge_graph_with_text.png`     | Graph with labeled nodes and directional edges    |
| `knowledge_graph_no_labels.png`     | Clean version for overlays or visual design       |
| `assets/repo-banner.png`            | GitHub social preview/banner image                |
| `requirements.txt`                  | Python packages required (for reproducibility)    |

---

## ⚙️ Technical Note (Optional)

The graph was generated using `networkx` and `matplotlib` in Python, with a locked layout for consistent node placement. Although not required to view or interpret the graph, the included script (`graph_generator.py`) allows full regeneration or customization of the visualization.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 👤 Author

Developed by **[@emclamo](https://github.com/emclamo)**  
Affiliation: STEPS Center (Science and Technologies for Phosphorus Sustainability)
