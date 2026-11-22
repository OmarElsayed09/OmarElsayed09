# Portfolio verification and engineering evidence

This page distinguishes **verified automated checks** from untested production claims for the four public AI/ML repositories.

| Repository | Evidence | Limits |
| --- | --- | --- |
| [LLM-RAG-Chatbot](https://github.com/OmarElsayed09/LLM-RAG-Chatbot) | [Real-embedding retrieval evaluation](https://github.com/OmarElsayed09/LLM-RAG-Chatbot/actions/runs/45061756395); [real Gradio home-screen capture](https://github.com/OmarElsayed09/LLM-RAG-Chatbot/actions/runs/45061756415); [unit/contract checks](https://github.com/OmarElsayed09/LLM-RAG-Chatbot/actions) | Four synthetic labeled questions reached 100% Hit@1 and 100% Recall@1; **not** a real-document benchmark or generated-answer evaluation |
| [Hotel Booking Prediction](https://github.com/OmarElsayed09/Hotel-Booking-Cancellation-ADR-Prediction) | [FastAPI HTTP smoke tests](https://github.com/OmarElsayed09/Hotel-Booking-Cancellation-ADR-Prediction/actions/runs/45061958828); [model validation tests](https://github.com/OmarElsayed09/Hotel-Booking-Cancellation-ADR-Prediction/actions/runs/45061958920); [actual static UI preview](https://github.com/OmarElsayed09/Hotel-Booking-Cancellation-ADR-Prediction/actions/runs/45061958829) | Historical stored model metrics not independently reproduced here; static UI screenshot is not evidence of working inference |
| [MediRAG](https://github.com/OmarElsayed09/medirag-clinical-assistant) | [Clinical calculator/security-rule tests](https://github.com/OmarElsayed09/medirag-clinical-assistant/actions/runs/45061900664); [actual static frontend preview](https://github.com/OmarElsayed09/medirag-clinical-assistant/actions/runs/45061900543) | No clinician-reviewed validation or real patient-care safety claim; UI no longer preloads unverified metrics |
| [Emergency Response](https://github.com/OmarElsayed09/smart-emergency-incident-response) | [LangGraph fan-out/fan-in integration](https://github.com/OmarElsayed09/smart-emergency-incident-response/actions/runs/45062008307); [structure/simulation checks](https://github.com/OmarElsayed09/smart-emergency-incident-response/actions) | Mock agents confirm graph structure only; no real dispatch, procedure corpus, or end-to-end external-provider validation |

**Important:** A GitHub Actions badge or a screenshot proves only the specific check it records. It does not establish application availability, cloud deployment, security certification, clinical validity, or generalization to new data.

## Review standard

1. Record a commit SHA and dependency versions for every metric.
2. Keep benchmarks tied to labeled data and disclose whether samples are synthetic.
3. Run unit, integration, API, and deployment smoke tests separately.
4. Show real UI captures without fictional outputs.
5. Validate model scores on unseen, appropriate real-world data before presenting them as performance claims.
6. Never publish API keys, patient records, or confidential business documents.

Artifacts attached to GitHub Actions may expire according to repository retention settings. Source test code and evaluation scripts remain in the repositories.
