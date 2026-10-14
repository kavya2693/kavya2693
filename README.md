<!-- Profile README for github.com/kavya2693 -->

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Kavyasri%20Jadala&fontColor=eef1f7&fontSize=54&fontAlignY=38&desc=Senior%20Data%20Scientist%20%C2%B7%20Forecasting%20%C2%B7%20Supply%20Planning%20%C2%B7%20Applied%20AI&descSize=18&descAlignY=60" alt="Kavyasri Jadala, Senior Data Scientist"/>

<a href="https://kavya2693.github.io">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1000&color=7CF0C8&center=true&vCenter=true&width=760&lines=Senior+Data+Scientist;Demand+Forecasting+%C2%B7+Supply+Planning;Inventory+%26+Logistics+Optimization+%C2%B7+Applied+AI;8.5%2B+years+%C2%B7+retail%2C+supply+chain%2C+quick-commerce%2C+healthcare" alt="Demand Forecasting · Supply Planning · Inventory & Logistics Optimization · Applied AI"/>
</a>

**Senior Data Scientist | Demand Forecasting · Supply Planning · Inventory & Logistics Optimization · Applied AI**

8.5+ years across retail, supply chain, grocery/quick-commerce and healthcare · Dubai, UAE (Golden Visa) · M.S. Purdue

[Portfolio](https://kavya2693.github.io) · [LinkedIn](https://www.linkedin.com/in/kavyasri-jadala) · [kavyasri.2693@gmail.com](mailto:kavyasri.2693@gmail.com)

</div>

---

### `MATCH (me) RETURN who`

```cypher
CREATE (me:DataScientist {
  name:      "Kavyasri Jadala",
  role:      "Senior Data Scientist",
  focus:     ["Demand Forecasting", "Supply Planning",
              "Inventory & Logistics Optimization", "Applied AI"],
  also:      ["Knowledge Graphs", "Graph-RAG", "Agentic AI"],
  domains:   ["Retail", "Supply Chain", "Grocery / Quick-commerce", "Healthcare"],
  based_in:  "Dubai, UAE  ·  Golden Visa",
  education: "M.S., Purdue University"
})
RETURN me.rule;

// ▸ "Score the model on the decision it drives, and report where it loses."
```

---

## Featured work

Each repo: problem-first README and results including what didn't win; most also carry an architecture section, tests and CI.

#### Forecasting & demand

| Repo | Problem | Headline result |
|---|---|---|
| [intermittent-demand-forecasting](https://github.com/kavya2693/intermittent-demand-forecasting) | Which forecasting method to run per SKU when nearly half the catalogue sells nothing in most weeks | Weekly WAPE 58.1% → 42.5% vs seasonal naive across 1,500 SKUs |
| [order-forecast-inventory](https://github.com/kavya2693/order-forecast-inventory) | Customer × SKU order forecasts for a B2B distributor, judged by the stock they let the warehouse hold | Holding cost at 98% fill −46.8% vs ETS |
| [retail-demand-forecasting](https://github.com/kavya2693/retail-demand-forecasting) | Store × SKU replenishment forecasts, with an ablation on whether a product/store graph earns its place | WMAPE 0.2273 → 0.1838 (19% lower) vs seasonal naive; graph lift only +0.4% |
| [peak-capacity-planner](https://github.com/kavya2693/peak-capacity-planner) | Riders per grocery hub and shift through Ramadan and a 4x mega-sale, checked order by order in a replay | On time 76.9% → 98.9% of accepted orders, 17.6% less spent on riders |

#### Inventory & supply planning

| Repo | Problem | Headline result |
|---|---|---|
| [ddmrp-buffers](https://github.com/kavya2693/ddmrp-buffers) | How much stock a lubricants distributor releases with DDMRP buffers, at the service level customers get today | Days of inventory 97.6 → 52.1 (−47%) at matched 98.46% fill |
| [agentic-supply-planning](https://github.com/kavya2693/agentic-supply-planning) | Forecasts turned into budgeted, approved purchase orders by a LangGraph supervisor and four agents | 88% touchless PO rate on the retail range |
| [supply-chain-twin](https://github.com/kavya2693/supply-chain-twin) | Test replenishment, promotion and fleet changes on a SimPy twin of a retail chain before any store sees them | −16.6% total cost on the tuned quarter; the same plan fails with 20% of the fleet out |

#### Routing & last mile

<a href="https://github.com/kavya2693/fleet-routing-cvrp"><img src="https://raw.githubusercontent.com/kavya2693/fleet-routing-cvrp/main/docs/demo/demo.gif" width="420" alt="fleet-routing-cvrp walkthrough"/></a>

| Repo | Problem | Headline result |
|---|---|---|
| [fleet-routing-cvrp](https://github.com/kavya2693/fleet-routing-cvrp) | Next-day routes for a 300-truck freight fleet with OR-Tools, and which lever actually cuts misrouted shipments | Peak-week road km −22.1% vs sweep baseline |
| [last-mile-dispatch](https://github.com/kavya2693/last-mile-dispatch) | 30-minute grocery dispatch across 26 dark-store hubs, judged by a hub-level A/B test | Fleet cost per delivered order −1.04 AED (−10.6%) |

#### Pricing & commercial

| Repo | Problem | Headline result |
|---|---|---|
| [markdown-optimizer](https://github.com/kavya2693/markdown-optimizer) | How deep to mark down each slow-moving grocery SKU, from its own elasticity instead of a blanket 30% off | Promotional margin +37,750 ± 8,252 vs the 30% rule |
| [order-outcome-margin](https://github.com/kavya2693/order-outcome-margin) | Which marketplace orders will lose money, and when to switch off cash on delivery | COD margin rule +22,258 (+0.72%) where blocking all COD loses 16.6% |
| [hcp-graph-targeting](https://github.com/kavya2693/hcp-graph-targeting) | Which doctors a launch sales team should call when prescription deciles stop separating converters | Converters in a 5% call plan: 126 (decile list) → 212 (graph features + embeddings) |
| [genai-recommender](https://github.com/kavya2693/genai-recommender) | Next content, channel and compliant message for 20,000 prescribers | BERT4Rec NDCG@10 0.303 loses to a last-item Markov chain at 0.316 |

#### Agents, LLMs & data platforms

| Repo | Problem | Headline result |
|---|---|---|
| [llm-cost-router](https://github.com/kavya2693/llm-cost-router) | Send each LLM request to the cheapest self-hosted model likely to get it right, and escalate only on a failed check | 61% cost saved vs all-large; completion 82.5% vs 85.0% |
| [agentic-pipeline-builder](https://github.com/kavya2693/agentic-pipeline-builder) | Messy source exports in; a typed, tested dbt project, a quarantine and an Airflow DAG out | Column types 54/54 (100%) vs 44/54 for DuckDB auto-detect |
| [novacart-mlops](https://github.com/kavya2693/novacart-mlops) | Churn, demand forecasting and a Graph-RAG assistant served as one MLOps stack | Churn ROC-AUC 0.795; logistic regression beat gradient boosting (0.772) |
| [predictive-maintenance](https://github.com/kavya2693/predictive-maintenance) | Which pumps, compressors and heat exchangers to service this week on a six-job crew budget | Cost per year 5.27M → 2.02M vs run-to-failure |

#### Knowledge graphs & governance

| Repo | Problem | Headline result |
|---|---|---|
| [customer360-ontology-graph](https://github.com/kavya2693/customer360-ontology-graph) | A customer-360 graph that rejects malformed entities at ingestion and answers questions from the graph, with citations | SHACL gate rejects the injected fault |
| [ontoloop](https://github.com/kavya2693/ontoloop) | Adverse drug event narratives into a knowledge graph, repaired until a SHACL validator passes | 3B model conformance 0% → 85% with the loop; accuracy does not improve |
| [mdm-entity-resolution](https://github.com/kavya2693/mdm-entity-resolution) | The same doctors across CRM, offline and web data resolved into golden records | Pairwise precision ~0.93, recall ~0.84 |
| [commercial-metadata-catalog](https://github.com/kavya2693/commercial-metadata-catalog) | Glossary, catalog and lineage that trace a marketing slide back to its source content and approval | Demonstration; no headline metric |
| [blastradius](https://github.com/kavya2693/blastradius) | Column-level lineage that reaches the application code a column change will break | 100% precision, 90% recall (27 / 0 / 3) on labelled references |

---

### `cat /skills`

**Forecasting, ML & optimization**

![Python](https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479a1?style=flat-square&logo=postgresql&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-f7931e?style=flat-square&logo=scikitlearn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-2c5364?style=flat-square)
![XGBoost](https://img.shields.io/badge/XGBoost-006400?style=flat-square)
![statsmodels](https://img.shields.io/badge/statsmodels-4b5563?style=flat-square)
![PyTorch](https://img.shields.io/badge/PyTorch-ee4c2c?style=flat-square&logo=pytorch&logoColor=white)
![PyTorch Geometric](https://img.shields.io/badge/PyTorch%20Geometric-3c2179?style=flat-square&logo=pyg&logoColor=white)
![OR-Tools](https://img.shields.io/badge/OR--Tools-4285f4?style=flat-square&logo=google&logoColor=white)
![PuLP](https://img.shields.io/badge/PuLP%20(MIP)-1a5276?style=flat-square)
![SimPy](https://img.shields.io/badge/SimPy-117864?style=flat-square)

**LLMs & agents**

![LangGraph](https://img.shields.io/badge/LangGraph-1c3c3c?style=flat-square&logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1c3c3c?style=flat-square&logo=langchain&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![Graph--RAG](https://img.shields.io/badge/Graph--RAG-7cf0c8?style=flat-square&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

**Knowledge graphs**

![Neo4j](https://img.shields.io/badge/Neo4j-018bff?style=flat-square&logo=neo4j&logoColor=white)
![Cypher](https://img.shields.io/badge/Cypher-2c5364?style=flat-square)
![RDF / OWL](https://img.shields.io/badge/RDF%20%2F%20OWL-005a9c?style=flat-square)
![SHACL](https://img.shields.io/badge/SHACL-117864?style=flat-square)
![SPARQL](https://img.shields.io/badge/SPARQL-0b5345?style=flat-square)
![NetworkX](https://img.shields.io/badge/NetworkX-2c5364?style=flat-square)

**Data platforms & MLOps**

![DuckDB](https://img.shields.io/badge/DuckDB-fff000?style=flat-square&logo=duckdb&logoColor=black)
![dbt](https://img.shields.io/badge/dbt-ff694b?style=flat-square&logo=dbt&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017cee?style=flat-square&logo=apacheairflow&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194e2?style=flat-square&logo=mlflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ed?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326ce5?style=flat-square&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088ff?style=flat-square&logo=githubactions&logoColor=white)

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

<i>"A forecast is only as good as the stock, routes and orders it changes. I measure that part."</i>

<img src="https://komarev.com/ghpvc/?username=kavya2693&style=flat-square&color=2c5364&label=Profile+Views"/>

</div>
