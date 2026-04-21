
# 🚗 Dynamic Pricing Engine for Urban Parking Lots  
**Capstone Project | Summer Analytics 2025**  
_By Consulting & Analytics Club, IIT Guwahati × Pathway_

---

## 🧠 Course Background

**Summer Analytics 2025** is a free, online 5‑week bootcamp (plus capstone week) designed for beginners aiming to build a strong foundation in data science and machine learning. It’s led by the Consulting & Analytics Club (C&A) at IIT Guwahati—known for reaching 25K+ students across 60+ countries and producing 300+ hours of content.

**Key highlights:**
- No prerequisites—just curiosity and a computer  
- Covers Python, data cleaning, visualization, ML (supervised + unsupervised), tree‑based models, neural networks, and real‑time data streaming  
- Industry‑relevant modules like Kafka and Pathway for streaming pipelines  
- Includes weekly tasks, webinars, mini‑hackathons, and a live capstone project with a hard deadline (July 9, 2025)  

---

## 📅 Live Sessions

Expert-led webinars included:

| Session | Speaker | Date | Topic |
|--------|---------|------|-------|
| 1 | Aditi Agrawal | May 25, 2025 | Intro & Data Analysis |
| 2 | Tarun Jain | June 1, 2025 | Advanced ML & Model Tuning |
| 3 | Abhineet Gupta | June 7, 2025 | MLOps: Model → Production |
| 4 | Ashish Jangra | June 15, 2025 | First AI Agent with Agentforce |
| 5 | Pranav Durai | June 22, 2025 | CNNs with PyTorch |
| 6 | Yashu Gupta | June 24, 2025 | AI in Fintech |
| 7 | Abhineet Gupta | June 28, 2025 | LLMs & Language Leverage |
| 8 | Sergey Kulik | June 30, 2025 | Real‑Time Data with Pathway |

---

## 🧩 Capstone Project Overview

**Our project** tackles a real-world problem—dynamic pricing for urban parking lots—using models that:
- Start simple (baseline linear pricing)  
- Incorporate demand features  
- Finally integrate competitor data and real-time updates via Pathway  

This aligns perfectly with the capstone requirements and industry applications of the course.

---

## 🛠️ Tech Stack & Tools

| Tool / Library      | Purpose |
|---------------------|---------|
| **Python**          | Core scripting |
| **Pandas, NumPy**   | Data processing |
| **Pathway**         | Real‑time streaming & pipeline |
| **Kafka** (theory)  | Data ingestion design (covered in course) |
| **Bokeh**           | Interactive visualizations |
| **Google Colab**    | Cloud notebook environment |
| **Mermaid**         | Architecture diagrams |
| **GitHub**          | Version control & submission |

---

## ⚙️ Architecture Diagram

```
flowchart TD
    A[CSV Data Stream Simulation] --> B[Pathway Engine]
    B --> C[Feature Engineering + Demand Estimation]
    C --> D[Pricing Models (Baseline → Demand → Competitive)]
    D --> E[Price Output per Lot]
    E --> F[Bokeh Dashboard]
    E --> G[Competitor Rerouting Logic]
```

---

## 🔍 Project Structure

```
.
├── README.md
├── baseline_model.ipynb        # Model 1 – Linear Pricing
├── demand_model.ipynb          # Model 2 – Demand‑Based Pricing
├── competitive_model.ipynb     # Model 3 – Competitive Pricing
├── pathway_simulation.py       # Real‑time streaming logic
├── bokeh_dashboard.ipynb       # Visualization dashboard
├── dataset.csv                 # Input parking data
├── baseline_pricing_output.csv
├── architecture_diagram.png    # Exported Mermaid diagram (optional)
├── Report.pdf (optional)       # Detailed documentation
└── requirements.txt            # Python package dependencies
```

---

## 📄 Documentation

✅ **README.md** – high-level overview, architecture, and instructions  
✅ **Notebooks & scripts** – well-documented code for all models and simulations  
📄 **Report.pdf** – optional deep dive into assumptions, formulas, and workflows  

---

## 📌 Submission Checklist

- [x] README with course & project info  
- [x] Tech stack, architecture, and project structure  
- [x] Mermaid diagram  
- [x] All three models implemented from scratch  
- [x] Integration of Pathway for real-time simulation  
- [x] Interactive Bokeh visualizations  
- [x] Capstone output file and optional PDF report  

---

## 📚 What You’ll Gain

After completing this project, you’ll:
- Understand core ML workflows from data ingestion to visualization  
- Build end-to-end dynamic systems using real-time streams (Pathway/Kafka)  
- Gain hands-on experience with models, dashboards, and deployment pipelines  
- Participate in prestigious webinars with experts like Sergey Kulik & Abhineet Gupta  

---

## 🚀 Let’s Get Started!

Clone the repository, install dependencies with `pip install -r requirements.txt`, and run **baseline_model.ipynb** to begin your journey 🚀

---

*This README follows the structure mandated by the Summer Analytics Capstone submission guidelines, enriched with live course details and technical context for clarity and completeness.*
