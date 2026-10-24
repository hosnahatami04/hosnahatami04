<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img alt="Hosna Hatami, AI engineer" src="assets/banner-light.svg" width="100%">
</picture>

<p align="center">
  <a href="https://www.linkedin.com/in/hosna-hatami"><img src="https://img.shields.io/badge/LinkedIn-hosna--hatami-5D5294?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:hosnahatami04@gmail.com"><img src="https://img.shields.io/badge/Email-hosnahatami04%40gmail.com-2B2741?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Open%20to-remote%20AI%20roles-8C82BE?style=flat-square" alt="Open to remote AI roles">
</p>

Most AI demos only show the happy path. In my projects the evaluation is the main part: a hand-built test set, a simple baseline to beat, every number read from a committed results file, and an honest section on what didn't work.

## Featured projects

<table>
<tr>
<td width="50%" valign="top">

### [agentic-task-runner](https://github.com/hosnahatami04/agentic-task-runner)
ReAct agent written from scratch, plus a harness that breaks its tools on purpose.

**Result:** task success holds at 71% with 10% tool faults and drops to 54% at 30%.

<sub>Agents · Ollama · fault injection · pytest</sub>

</td>
<td width="50%" valign="top">

### [technical-docs-rag](https://github.com/hosnahatami04/technical-docs-rag)
Answers questions on the PostgreSQL docs, and says "I don't know" when the answer isn't there.

**Result:** caught 13 of 15 unanswerable questions; 92% of answer sentences backed by a source.

<sub>Hybrid retrieval · BM25 + dense + RRF · grounding gates</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [ml-drift-monitoring](https://github.com/hosnahatami04/ml-drift-monitoring)
Drift detectors written from scratch, alerting, and a harness that scores the monitor itself.

**Result:** sudden drift caught in the first window on every test stream; 6.7% false alarms on drift-free streams.

<sub>MLOps · KS / PSI / Page-Hinkley · Prometheus · FastAPI</sub>

</td>
<td width="50%" valign="top">

### [casting-defect-detection](https://github.com/hosnahatami04/casting-defect-detection)
Pass, reject or manual-review decisions for metal castings, set from the cost of each error.

**Result:** zero escaped defects on the test set, 1.9% false rejects, 11.8 ms p95 on CPU.

<sub>Computer vision · calibration · ONNX · cost-aware thresholds</sub>

</td>
</tr>
</table>

## More projects

| Project | What it does | Result |
|---|---|---|
| [ecommerce-recommender](https://github.com/hosnahatami04/ecommerce-recommender) | Popularity, ALS and a two-stage reranker on 2.7M real events | Only the two-stage model beats the popularity baseline on every headline metric |
| [multimodal-image-search](https://github.com/hosnahatami04/multimodal-image-search) | CLIP text-to-image search and BLIP visual QA, on CPU | Recall@10 of 0.569 on Flickr8k, with failures broken down by category |
| [crypto-volatility-forecasting](https://github.com/hosnahatami04/crypto-volatility-forecasting) | GARCH vs LSTM vs hybrid for next-24h volatility, walk-forward | GARCH beat both deep models on QLIKE; its edge over a 7-day mean was not significant |

Every repo uses public data and comes with tests, CI and a Dockerfile.

## Now building

**support-ticket-intelligence:** routing and priority for support tickets, with abstention when the model isn't sure and summaries checked for faithfulness.<br>
**speech-to-insight:** from meeting audio to decisions and action items, measuring how transcription errors spread down the pipeline.

## Stack

<p>
  <img src="https://img.shields.io/badge/Python-2B2741?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PyTorch-2B2741?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/Transformers-2B2741?style=flat-square&logo=huggingface&logoColor=white" alt="Transformers">
  <img src="https://img.shields.io/badge/scikit--learn-2B2741?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/FastAPI-2B2741?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/Docker-2B2741?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Ollama-2B2741?style=flat-square&logo=ollama&logoColor=white" alt="Ollama">
  <img src="https://img.shields.io/badge/PostgreSQL-2B2741?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/GitHub%20Actions-2B2741?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions">
</p>
