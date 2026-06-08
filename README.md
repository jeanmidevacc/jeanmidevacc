<!--
  This file is the README for the jeanmidevacc/jeanmidevacc GitHub profile repository.
  Copy it to that repo as README.md.

  To enable auto-updating recent blog posts, also create the file at:
    .github/workflows/update-blog-posts.yml
  with the content shown at the bottom of this file.
-->

<div align="center">

# Jean-Michel Daignan

**Senior Data Scientist & ML Engineer · [The Odd Dataguy](https://www.the-odd-dataguy.com)**

[![Blog](https://img.shields.io/badge/Blog-the--odd--dataguy.com-7dcfff?style=flat-square&logo=jekyll&logoColor=white)](https://www.the-odd-dataguy.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-jeanmicheldaignan-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jeanmicheldaignan/)
[![Bluesky](https://img.shields.io/badge/Bluesky-daignanjm-0085ff?style=flat-square&logo=bluesky&logoColor=white)](https://bsky.app/profile/daignanjm.bsky.social)
[![Kaggle](https://img.shields.io/badge/Kaggle-jeanmidev-20BEFF?style=flat-square&logo=kaggle&logoColor=white)](https://www.kaggle.com/jeanmidev)

</div>

---

10 years building data and ML systems — energy sector in France and the UK first, then gaming in Montreal. Currently a Senior Data Scientist in Ubisoft's Canadian Analytics Team: recommender systems, ML platforms, in-game personalization across multiple AAA titles.

I write about what I actually build at **[the-odd-dataguy.com](https://www.the-odd-dataguy.com)** — 50+ posts on MLOps, recommender systems, data engineering, and occasional side projects that spiral into something interesting.

---

## What I work on

**MLOps & Production ML**  
Five years building Ubisoft's in-house ML platform from scratch, now on Databricks. I care about the gap between "model that works in a notebook" and "model that's still running at 3am without you."

**Recommender Systems**  
Cold start problems, marketplace recommendations, in-game content discovery. Main focus for the last several years across multiple titles (Rainbow Six Siege, Assassin's Creed, and more).

**Data Engineering**  
Pipelines, ETL, web scraping infrastructure. The unsexy parts that everything else depends on.

**Data Investigation**  
Turning raw, messy datasets into something actionable — from IoT sensor streams (EDF) to customer call transcripts to gaming telemetry. POC-first, no hype.

---

## Stack

**Core**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)

**Data Engineering**  
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![MongoDB](https://img.shields.io/badge/NoSQL/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

**Machine Learning**  
![Scikit--learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Spark MLlib](https://img.shields.io/badge/Spark%20MLlib-E25A1C?style=flat-square&logo=apachespark&logoColor=white)

**MLOps & Platforms**  
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**Apps & Reporting**  
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-F97316?style=flat-square&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly/Dash-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)

**Scraping & Pipelines**  
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Scrapy](https://img.shields.io/badge/Scrapy-60A839?style=flat-square&logoColor=white)

---

## Recent posts

<!-- BLOG-POST-LIST:START -->
<!-- BLOG-POST-LIST:END -->

*Auto-updated · full archive at [the-odd-dataguy.com/en/blog](https://www.the-odd-dataguy.com/en/blog/)*

---

## Open to consulting

Web scraping systems · AI operationalization · Data investigation · Technical talks

→ [the-odd-dataguy.com/en/consulting](https://www.the-odd-dataguy.com/en/consulting/)

---

<div align="center">

![GitHub stats](https://github-readme-stats.vercel.app/api?username=jeanmidevacc&theme=tokyo-night&show_icons=true&hide_border=true&count_private=true&include_all_commits=true)
&nbsp;
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=jeanmidevacc&theme=tokyo-night&hide_border=true&layout=compact&langs_count=6)

</div>

---

<!--
=============================================================
GITHUB ACTION — auto-updates the "Recent posts" section above
=============================================================

Create this file in your jeanmidevacc repo:
  .github/workflows/update-blog-posts.yml

---

name: Update README with latest blog posts
on:
  schedule:
    - cron: '0 */6 * * *'   # runs every 6 hours
  workflow_dispatch:          # allows manual trigger from GitHub UI

jobs:
  update-readme:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - uses: gautamkrishnar/blog-post-workflow@master
        with:
          feed_list: "https://www.the-odd-dataguy.com/feed.xml"
          max_post_count: 5
          readme_path: README.md
          comment_tag_name: BLOG-POST-LIST

=============================================================
-->
