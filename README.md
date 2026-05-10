# Collective Mind — Backend Architecture & QA Case Study

⚠️ **Note:** This repository contains the architectural overview and testing reports. The source code is private.

## 1. System Architecture & Modular Design
<img width="1440" height="900" alt="1Снимок экрана — 2026-05-10 в 13 34 36" src="https://github.com/user-attachments/assets/7697fa9f-5000-44dd-a168-30aff65c4ff0" />
* **Structure:** Clearly separated modules (`users`, `works`) following Django best practices.
* **Integrity:** Use of `serializers.py` for data validation and `models.py` for DB schema design.

## 2. API Verification (Postman & JS Tests)
<img width="1440" height="900" alt="2Снимок экрана — 2026-05-10 в 13 35 15" src="https://github.com/user-attachments/assets/235b4cbb-682e-485b-af52-d9cd61a51230" />
* **Automated Checks:** Implemented JavaScript test snippets to verify status codes and response headers.
* **End-to-End:** Ensured the backend delivers correct HTML/JSON structure for Frontend consumption.

## 3. Testing Strategy & Coverage Analysis
<img width="1440" height="900" alt="3Снимок экрана — 2026-05-10 в 13 38 48" src="https://github.com/user-attachments/assets/fb2775a1-98ba-486e-911a-76213915a90f" />
* **Reliability:** Critical business logic (serializers and models) achieved **95-100% test coverage**.
* **Global Quality:** Total project coverage stands at **81%** (Pytest).

## 4. Deployment & Environment Setup
<img width="1440" height="900" alt="4Снимок экрана — 2026-05-10 в 13 36 01" src="https://github.com/user-attachments/assets/49fa84f8-e23b-4894-9e45-18c98262ec66" />
* **Reproducibility:** Standardized setup via `pip install -r requirements.txt`.
* **Infrastructure:** Ready for containerization with `Dockerfile` and structured environment configs.

---
**Tech Stack:** Python, Django REST Framework, Pytest, Coverage.py, Postman, Redmine.
