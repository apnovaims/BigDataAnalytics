# F1 Strategy Platform — PySpark Big Data Analytics

End-to-end PySpark platform for Formula 1 constructor decision-making, covering batch analysis, machine learning, graph analytics and streaming.

Course project for Big Data Analytics, MSc in Data Science and Advanced Analytics, NOVA IMS (2026).

## What the project does

- **Ingestion:** loads race data with RDDs and Spark DataFrames.
- **Analysis:** explores the data in Spark SQL, including window functions.
- **Machine learning:** builds MLlib pipelines tuned with CrossValidator and ParamGridBuilder.
- **Graph analytics:** uses GraphFrames for PageRank, Connected Components, BFS and motif finding.
- **Streaming:** processes events with Structured Streaming, using watermarking and windowed aggregations.

## Repository contents

| File | Description |
| --- | --- |
| `F1_Strategy_Platform_Presentation.pdf` | Project presentation |
| `F1_PySpark_Project_Proposal.md` | Project proposal |
| `Notebook_1.ipynb` | Data ingestion |
| `Notebook_2_EDA_and_flow_chart.ipynb` | Exploratory analysis and flow chart |
| `Notebook_3_ML.ipynb` | Machine-learning pipelines |
| `Notebook_4_Graphs.ipynb` | Graph analytics |
| `Notebook_5_Streaming.ipynb` | Structured Streaming |
| `f1_driver_flow.ipynb`, `driver_flow.png` | Driver flow diagram |
| `helpers.py` | Shared helper functions |
| `data/` | Input data |
| `ml_artifacts/` | Saved model artefacts |

## Tech stack

PySpark · Spark SQL · MLlib · GraphFrames · Structured Streaming

## Authors

Artem Polikarpov · [LinkedIn](https://www.linkedin.com/in/artem-polikarpov-068a4313) · [All projects](https://github.com/apnovaims)
Khuzaima Bashir, 
Muhammad Ammar, 
Sapana Dhami, 
Simon Sazonov
