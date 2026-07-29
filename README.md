<!-- Profile README for github.com/kavya2693 -->

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Kavyasri%20Jadala&fontColor=eef1f7&fontSize=54&fontAlignY=38&desc=Senior%20AI%2FML%20%C2%B7%20Knowledge%20Graphs%20%C2%B7%20Graph-RAG&descSize=18&descAlignY=60" alt="header"/>

<a href="https://kavya2693.github.io">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1000&color=7CF0C8&center=true&vCenter=true&width=720&lines=Knowledge+Graphs+%7C+Graph-RAG+%7C+Semantic+AI;LLM+%26+GenAI+pipelines+you+can+trust+in+production;Forecasting+%C2%B7+Optimisation+%C2%B7+MLOps;8%2B+years+across+healthcare%2C+energy+%26+e-commerce" alt="typing"/>
</a>

</div>

---

### `MATCH (me) RETURN who`

```cypher
CREATE (me:Engineer:Leader {
  name:      "Kavyasri Jadala",
  role:      "Senior Manager — AI/ML & Data Products",
  based_in:  "Dubai, UAE  ·  Golden Visa",
  focus:     ["Knowledge Graphs", "Graph-RAG", "GenAI", "MLOps"],
  domains:   ["Healthcare/Pharma", "Energy", "E-commerce", "Supply Chain"],
  education: "M.S. Data Science, Purdue University"
})
MATCH (me)-[:BUILDS]->(system:MLSystem)
WHERE system.verified = true          // the part everyone skips
RETURN me.mission;

// ▸ "Build machine-learning systems you can actually trust in production."
```

---

### `cat /skills`

**Knowledge Graphs & Semantics**

![Neo4j](https://img.shields.io/badge/Neo4j-018bff?style=flat-square&logo=neo4j&logoColor=white)
![AWS Neptune](https://img.shields.io/badge/AWS%20Neptune-232f3e?style=flat-square&logo=amazonaws&logoColor=white)
![RDF](https://img.shields.io/badge/RDF-005a9c?style=flat-square)
![OWL](https://img.shields.io/badge/OWL-1a5276?style=flat-square)
![SHACL](https://img.shields.io/badge/SHACL-117864?style=flat-square)
![SPARQL](https://img.shields.io/badge/SPARQL-0b5345?style=flat-square)
![Cypher](https://img.shields.io/badge/Cypher-2c5364?style=flat-square)
![GraphQL](https://img.shields.io/badge/GraphQL-e10098?style=flat-square&logo=graphql&logoColor=white)

**LLM · RAG · GenAI**

![LangChain](https://img.shields.io/badge/LangChain-1c3c3c?style=flat-square&logo=langchain&logoColor=white)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-000000?style=flat-square)
![Graph--RAG](https://img.shields.io/badge/Graph--RAG-7cf0c8?style=flat-square&logoColor=black)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square&logo=pinecone&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-4b8bbe?style=flat-square)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-ffd21e?style=flat-square&logo=huggingface&logoColor=black)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)

**Machine Learning**

![Python](https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-ee4c2c?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-ff6f00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-f7931e?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-006400?style=flat-square)
![LightGBM](https://img.shields.io/badge/LightGBM-2c5364?style=flat-square)

**Data Engineering & MLOps**

![dbt](https://img.shields.io/badge/dbt-ff694b?style=flat-square&logo=dbt&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017cee?style=flat-square&logo=apacheairflow&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194e2?style=flat-square&logo=mlflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ed?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326ce5?style=flat-square&logo=kubernetes&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479a1?style=flat-square&logo=postgresql&logoColor=white)

**Cloud & BI**

![AWS](https://img.shields.io/badge/AWS-232f3e?style=flat-square&logo=amazonaws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285f4?style=flat-square&logo=googlecloud&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078d4?style=flat-square&logo=microsoftazure&logoColor=white)
![SageMaker](https://img.shields.io/badge/SageMaker-232f3e?style=flat-square&logo=amazonaws&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-f2c811?style=flat-square&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-e97627?style=flat-square&logo=tableau&logoColor=white)

---

### `ls -la ~/pinned`

| Project | What it does |
|---|---|
| **[ontoloop](https://github.com/kavya2693/ontoloop)** | Agent loop that turns drug-safety narratives into a knowledge graph and repairs it until a SHACL validator passes — the verifier never calls a model. |
| **[blastradius](https://github.com/kavya2693/blastradius)** | Column-level lineage that doesn't stop at the warehouse edge: statically finds the *application code* a column change will break. |
| **[landcover-spatial-cv](https://github.com/kavya2693/landcover-spatial-cv)** | Satellite land-cover classification with spatial cross-validation that blocks leakage — an honest 95.8%, not an inflated one. |
| **[gulf-shield-osint](https://github.com/kavya2693/gulf-shield-osint)** | Arabic-native OSINT + desert-optimised SAR change detection for Gulf security — Western tools don't speak Arabic or work in deserts. |
| **[youtube-summarizer](https://github.com/kavya2693/youtube-summarizer)** | Video-intelligence app: transcript-first summarisation with a map-reduce path so long talks aren't truncated. |

---

<div align="center">

### `./stats.sh`

<img height="165" src="https://github-readme-stats.vercel.app/api?username=kavya2693&show_icons=true&hide_border=true&count_private=true&theme=react&bg_color=0d1117&title_color=7cf0c8&icon_color=7cf0c8&text_color=b7bfd0"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=kavya2693&layout=compact&hide_border=true&langs_count=8&theme=react&bg_color=0d1117&title_color=7cf0c8&text_color=b7bfd0"/>

<img height="165" src="https://streak-stats.demolab.com?user=kavya2693&hide_border=true&background=0d1117&stroke=7cf0c8&ring=7cf0c8&fire=7cf0c8&currStreakLabel=7cf0c8&sideLabels=b7bfd0&dates=b7bfd0&currStreakNum=eef1f7&sideNums=eef1f7"/>

<img src="https://github-profile-trophy.vercel.app/?username=kavya2693&theme=matrix&no-frame=true&no-bg=true&margin-w=6&column=7"/>

</div>

---

### `cat /certs`

![Neo4j Certified](https://img.shields.io/badge/Neo4j%20Certified%20Professional-018bff?style=flat-square&logo=neo4j&logoColor=white)
![AWS SA](https://img.shields.io/badge/AWS%20Solutions%20Architect-ff9900?style=flat-square&logo=amazonaws&logoColor=white)
![AWS CP](https://img.shields.io/badge/AWS%20Cloud%20Practitioner-ff9900?style=flat-square&logo=amazonaws&logoColor=white)
![CAP](https://img.shields.io/badge/Certified%20Analytics%20Professional-1a5276?style=flat-square)
![Power BI](https://img.shields.io/badge/Microsoft%20Power%20BI%20Analyst-f2c811?style=flat-square&logo=powerbi&logoColor=black)

---

<div align="center">

### `tail -f /connect`

<a href="https://kavya2693.github.io"><img src="https://img.shields.io/badge/Portfolio-7cf0c8?style=for-the-badge&logo=githubpages&logoColor=black"/></a>
<a href="https://www.linkedin.com/in/kavyasri-jadala"><img src="https://img.shields.io/badge/LinkedIn-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:kavyasri.2693@gmail.com"><img src="https://img.shields.io/badge/Email-ea4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>

<br/><br/>

<i>"The trustworthy part of a model is the part everyone skips. I build that part."</i>

<img src="https://komarev.com/ghpvc/?username=kavya2693&style=flat-square&color=2c5364&label=Profile+Views"/>

</div>
