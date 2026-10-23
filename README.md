<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=210&section=header&text=Dan%20Cernei&fontSize=58&fontColor=ffffff&fontAlignY=36&desc=Computer%20Science%20%C2%B7%20University%20of%20Bologna&descAlignY=57&descSize=18" width="100%" alt="banner"/>
</p>

<p align="center">
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=70A5FD&center=true&vCenter=true&width=640&lines=MSc+student+in+Computer+Science+%40+UniBo;Transfer+learning+for+survival+analysis;Transformers+on+clinical+tabular+data;Mobile+developer+behind+CrossingBO" alt="Typing SVG"/></a>
</p>

<p align="center">
  <a href="https://github.com/dancernei"><img src="https://img.shields.io/github/followers/dancernei?label=Followers&style=for-the-badge&logo=github&color=2c5364" alt="followers"/></a>
  <a href="https://www.linkedin.com/in/dan-cernei/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
</p>

---

Hi, I'm Dan. I'm finishing my MSc in Computer Science at the University of Bologna.

Most of my time goes into machine learning for healthcare, and in particular one question: can a model trained on one hospital's data be reused on a different cohort, where the columns, the patients and the missing values all look different? When I'm not doing that, I like building apps that people actually open on their phone, like **CrossingBO**.

```python
dan = {
    "based_in":   "Bologna, Italy",
    "studying":   "MSc Computer Science @ University of Bologna",
    "visited":    "School of Computing, Dublin City University (summer 2026)",
    "working_on": ["transfer learning for survival analysis", "clinical tabular data"],
    "building":   ["CrossingBO"],
    "speaks":     ["it", "en", "ru", "ro", "es", "de"],
}
```

## 🔬 Research: SurvBridge

> *A model pre-trained on a large database: can it help predict survival in a small cardiovascular cohort that doesn't even record the same variables?*

That's the question behind my master's thesis, **Integrating Clinical Data Towards a Multi-Center Embedding Model**, which started during a three-month research visit at Dublin City University.

<table>
<tr>
<td width="50%" valign="top">

**What the model does**

- Gives missing values their own **learned embedding**: in the original TransTab a missing value ended up looking like an average one
- **Contrastive pre-training** on MIMIC-IV, then **fine-tuning** with a Cox survival head on two Italian cardiovascular cohorts (URRAH and IHD)

</td>
</tr>
</table>

<p align="center">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/Slurm_HPC-1f6feb?style=flat-square&logoColor=white"/>
  <img src="https://img.shields.io/badge/MIMIC--IV-2ca02c?style=flat-square"/>
  <img src="https://img.shields.io/badge/Survival_Analysis-6f42c1?style=flat-square"/>
</p>

## 📱 Mobile: CrossingBO

<!-- Controlla che il link porti al repo giusto -->
**[CrossingBO](https://github.com/dancernei/CrossingBO)** plans jogging routes in Bologna with as few pedestrian crossings as possible, so you can keep running without stopping at every zebra crossing or traffic light. Pick a start, an end (or the same point for a loop) and a distance, and the app finds the route. My bachelor's thesis project.

- 🗺️ Pedestrian graph built from **OpenStreetMap**, with both sides of each street and crossings weighted by type
- ⚡ Modified **bidirectional Dijkstra**: a route in about 0.4 s on average, with almost no crossings
- 📱 **Flutter** app with Mapbox maps, a **Java** routing server, local history of your runs

<p>
  <img src="https://skillicons.dev/icons?i=flutter,dart,java,maven,python&perline=5" alt="CrossingBO stack"/>
</p>

## 🧰 Toolbox

<details open>
<summary><b>Languages</b></summary>
<br/>
<p>
  <img src="https://skillicons.dev/icons?i=python,java,kotlin,dart,js,ts,html,css,bash,latex&perline=10" alt="languages"/>
</p>
<p>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logoColor=white"/>
  <img src="https://img.shields.io/badge/Prolog-74283C?style=flat-square&logoColor=white"/>
  <img src="https://img.shields.io/badge/MiniZinc-DC3C22?style=flat-square&logoColor=white"/>
</p>
</details>

<details open>
<summary><b>Machine learning & data</b></summary>
<br/>
<p>
  <img src="https://skillicons.dev/icons?i=pytorch,sklearn,tensorflow,opencv&perline=8" alt="ml"/>
</p>
<p>
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white"/>
  <img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white"/>
</p>
</details>

<details open>
<summary><b>Mobile & web</b></summary>
<br/>
<p>
  <img src="https://skillicons.dev/icons?i=flutter,androidstudio,kotlin,firebase,react,nestjs,bootstrap&perline=8" alt="mobile and web"/>
</p>
</details>

<details>
<summary><b>Databases, tools & infrastructure</b></summary>
<br/>
<p>
  <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,sqlite,git,docker,linux,gradle,maven&perline=9" alt="tools"/>
</p>
<p>
  <img src="https://img.shields.io/badge/Slurm-1f6feb?style=flat-square&logoColor=white"/>
  <img src="https://img.shields.io/badge/tmux-1BB91F?style=flat-square&logo=tmux&logoColor=white"/>
  <img src="https://img.shields.io/badge/uv-DE5FE9?style=flat-square&logo=uv&logoColor=white"/>
  <img src="https://img.shields.io/badge/Google_Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=white"/>
</p>
</details>

## 🌍 Languages I speak

| | Language | Level |
|:-:|:--|:--|
| 🇮🇹 | Italian | Native |
| 🇬🇧 | English | C1 |
| 🇷🇺 | Russian | C1 |
| 🇷🇴 | Romanian | C1 |
| 🇪🇸 | Spanish | B1 |
| 🇩🇪 | German | A2 |



