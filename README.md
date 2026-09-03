# Ibrahim A. Makanjuola

**Software Engineer — AI systems and agentic AI**
Lagos, Nigeria · open to relocation and remote

I build the machinery around models rather than just calling them: serving open-weight LLMs on
GPUs, giving agents tools they can use safely, and squeezing models small enough to run on a
microcontroller. Backend engineering is the foundation that makes any of it shippable.

B.Eng. Electronics and Computer Engineering, Lagos State University (2026).

---

## Now

**Backend engineer at [De Cloud23 Technologies](https://decloud23tech.com/)**, on
[Games4Africa](https://games4africa.com) — the central hub for an African gaming platform.
Core services in Express and MySQL: relational schema design, player accounts and auth,
studio integrations into the hub, and wallet and rewards flows.

**Building Skyla**, an agentic life-automation platform where users compose sandboxed agents
that run long tasks and keep persistent context. *In development — private repos, nothing to
show publicly yet.*

---

## Selected work

**[artemis](https://github.com/Twilight-Techy/artemis)** — an AI smart-home agent that runs a
full agentic loop over voice and text: the model picks a tool, the tool executes, the result
is fed back, and the agent speaks the confirmation. Nothing physical happens until the model
has produced an explicit reasoning trace and the user has approved it. FastAPI and Gemini on
the backend, ESP32 firmware over MQTT at the edge, plus a simulator mirroring the firmware's
wire contract so the whole stack is developable without hardware.

**[kliniq-api](https://github.com/Twilight-Techy/kliniq-api)** — clinical triage across
English, Hausa, Igbo and Yoruba, built on N-ATLaS, an open-weight Nigerian multilingual model.
Served it myself on Modal A10G GPUs with vLLM — FP16, 8K context, cached weight volumes,
request concurrency for warm starts. The model has no native function calling, so tool use is
a call protocol I defined, parsed out of raw generations and executed transactionally.
*Awarri Developer Challenge 2025.*

**[ev-range-estimation-system](https://github.com/Twilight-Techy/ev-range-estimation-system)**
— range prediction for electric tricycles from a 60-second window of telemetry. An LSTM tuned
with KerasTuner Bayesian search, then quantized to INT8 so it fits a 120 KB tensor arena and
runs on a $5 ESP32 via TFLite Micro. The memory budget is the whole engineering problem.

**[attention-malaria-tb-detection](https://github.com/Twilight-Techy/attention-malaria-tb-detection)**
— implementation of an attention-improved diagnosis framework: CBAM attention modules dropped
into five architectures (custom CNN, ResNet50, VGG16, MobileNetV2, DenseNet121), with Grad-CAM
heatmaps for clinical interpretability. Built for a research project by Muhammed Toheeb
Abdulraheem.

**[scones-unlimited-ml-pipeline](https://github.com/Twilight-Techy/scones-unlimited-ml-pipeline)**
— event-driven image classification on AWS: Step Functions orchestrating Lambdas around a
SageMaker endpoint, with confidence thresholding and parallel fan-out.

**[crisp](https://github.com/Twilight-Techy/crisp)** — a crime reporting and incident
platform. Next.js, Prisma and PostgreSQL, with geospatial visualization through MapLibre and
CesiumJS.

---

## Working with

| | |
|---|---|
| **Languages** | Python, TypeScript, JavaScript, SQL, C++ (embedded), Java |
| **AI systems** | vLLM, Modal, tool and function calling, agent orchestration, Model Context Protocol, INT8 quantization, TFLite Micro, PyTorch, TensorFlow, Keras, OpenCV, YOLOv8 |
| **Backend** | FastAPI, NestJS, Express, Django, SQLAlchemy, asyncpg, Prisma, Pydantic, REST design, JWT and RBAC |
| **Data & infra** | PostgreSQL, MySQL, MS SQL Server, Redis, Docker, Azure DevOps CI/CD, AWS (SageMaker, Lambda, Step Functions, S3), MQTT |

Certified in Model Context Protocol (Anthropic), OCI Generative AI Professional and OCI
Multicloud Architect Professional (Oracle), and the AWS Machine Learning Nanodegree (Udacity).

---

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/ibrahim-makanjuola) ·
[X](https://x.com/iMaksxAI) ·
[mzone7325@gmail.com](mailto:mzone7325@gmail.com)

Also a Millennium Fellow, and I've spent the last two years volunteering as lead engineer and
mentor at the [Retgrow Initiative](https://github.com/Twilight-Techy/retgrow-learn), building
learning tools for underserved students in Nigeria.
