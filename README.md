# 🌊 Hidden Currents: Thermoelectric Cooling & Power Plant Anomaly Detection

> A messy but meaningful journey into public energy data, anomaly detection, and domain discovery.  
> Project duration: ~12 weeks | Tools: Python, pandas, seaborn, scikit-learn, Matplotlib
> Youtube: [YouTube: Project Walkthrough - *Hidden Currents – Water Data Quality 2015–2023*](https://youtu.be/vj5E-Mj2jR8)

---

## 🌱 Background & Motivation

This project was developed as my **CareerFoundry Data Analytics capstone**. This marked my first fully independent exploration—from data sourcing to modeling—into a topic of increasing urgency for us all: **energy and water**.

Initially, I wanted to explore water usage in data centers (as part of my growing interest in AI-human interaction and its real-world resource footprint). But data around water usage in data centers is largely proprietary and inaccessible. This challenge redirected me to a rich, publicly available source: the **U.S. Energy Information Agency (EIA)**. From there, I began exploring how water is consumed in **thermoelectric cooling** across power plants—a key area in the **water-energy nexus**.

---

## 🧠 Learning Through Doing (and Struggling)

There is no way to avoid it: this repo is messy.

There are 7 folders, each named after the CareerFoundry lesson/module I was in when I made progress. Rather than "cleaning" the history, I'm preserving it here for transparency—and as a record of how real-world projects evolve.

The project required:
- Navigating **multiple, complex datasets** that weren’t pre-cleaned, normalized, or even always mutually compatible.
- Building my own **understanding of the U.S. energy ecosystem** from scratch—fuel types, power plant classification, carbon emissions, water usage, etc.
- Experimenting with **data merging**, reconciliation, and schema issues—particularly around overlapping but incomplete plant records.
- Identifying **missingness patterns** and anomalies—what initially looked like reporting failure often turned out to be schema or unit variation.
- Dipping into **intro ML concepts**, including:
  - Agglomerative clustering
  - Anomaly scoring

---

## 🔍 Project Focus

After several false starts, I focused on:
- **Thermoelectric cooling water usage** data
- **Daily granularity** (very rich)
- Building anomaly scores for missing or suspicious entries
- Thinking through how this might inform **edge-AI auditing systems** for infrastructure oversight

---

## 💬 Reflections

This project was a crash course in:
- **Domain-driven thinking** (without domain expertise at the start)
- Why **data quality** is inseparable from policy, incentives, and reporting standards
- How **public data** can be incredibly rich but also incredibly unstructured
- The joys...and frustrations...of working with real-world data at scale (The number of folders I had named "AZ_Sysiphus" shall remaind undisclosed.)
- How much I’ve come to rely on, learn from, and co-develop ideas alongside tools like **ChatGPT and Perplexity AI**—this project unfolded in parallel with my curiosity around AI-human learning and the need to understand AI's environmental costs.

---

## 📌 Final Thoughts

This repo is a bit of cinéma vérité—and the vérité is this: data wrangling is brutal, project scoping is far from obvious, and staving off scope creep is a kind of proprioceptive skill. For me, I include this in my GitHub portfolio as a personal reminder of how much can be learned through endurance.

If you’re a fellow learner, I hope this project helps normalize the messiness of early-stage data work.

If you’re a reviewer or potential collaborator, I invite you to look past the folder structure (😅) and into the depth of curiosity, struggle, and persistence behind it.

Thanks for reading 🙏

—Amy
