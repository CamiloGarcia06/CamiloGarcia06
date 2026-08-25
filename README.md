# Juan Camilo Sandoval García — @CamiloGarcia06

Odoo & Python developer moving deeper into applied AI/ML and data engineering.
I build custom Odoo modules and portals by day, and I'm completing a Master's in
Artificial Intelligence — currently working on a computer-vision thesis on
multi-object tracking. Common thread across both: reproducible environments,
readable code, and documentation someone else can actually follow.

---

## What I do
- **Odoo (v12–v18):** accounting/portal features, custom models, controllers, XML/QWeb, security, OWL.
- **Backend:** Python (Odoo ORM), FastAPI, PostgreSQL, REST integrations.
- **Data & MLOps:** Apache Airflow, MLflow, Weights & Biases, MinIO/S3, idempotent pipelines.
- **ML & CV:** PyTorch, classical ML, deep learning, multi-object tracking (HOTA/MOTA/IDF1 via TrackEval).
- **DevOps:** Docker & Compose, Makefile/Taskfile, Git/GitHub, CI-ready project structure.

## Currently
- **Master's thesis:** overhead-view multi-object tracking to estimate directional
  passenger flows (boarding/alighting) in public transport under varying congestion.
- Building MLOps coursework end to end — orchestration, model registry, serving.
- Shipping Odoo work and standardizing project templates to spin environments up fast.

## Selected projects
- **[Multi-Object-Tracking](https://github.com/CamiloGarcia06/Multi-Object-Tracking)** — reproducible
  PyTorch/CUDA research environment for my MOT thesis: TrackEval metrics, W&B + MLflow tracking,
  JupyterLab in-container, Taskfile-driven. Built so a two-person team on Windows/macOS/Linux
  gets the same results.
- **[Mlops_talleres](https://github.com/CamiloGarcia06/Mlops_talleres)** — Covertype classification
  pipeline on Airflow: 4-stage DAG (validation → ingestion → transformation → cleaning),
  models in MinIO, real-time inference through a FastAPI service.
- **[technical_test_cun](https://github.com/CamiloGarcia06/technical_test_cun)** — Data engineering
  pipeline GitHub → PostgreSQL → Drive, orchestrated with Airflow. Idempotent loads,
  documented design decisions, one-command reproducibility from a clean clone.
- **[claude-fluent](https://github.com/CamiloGarcia06/claude-fluent)** — personal English-learning
  app on top of Anki: FastAPI backend, no-build frontend, card generation via `claude -p`.
- **[docker-odoo-18](https://github.com/CamiloGarcia06/docker-odoo-18)** — Makefile-driven
  Odoo 18 development environment.

## How I work
- Readable, well-structured code with docstrings and tests.
- Reproducibility first (Docker/Compose + Makefile/Taskfile + a README that actually works).
- Clear PRs: what changed, why it changed, and how it was validated.

## Contact
- **Email:** juancasangar@hotmail.com
- **LinkedIn:** https://www.linkedin.com/in/camilo-garcia-b50957168/
