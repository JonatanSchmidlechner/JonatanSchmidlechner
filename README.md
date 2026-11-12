# Welcome to My Portfolio! 👋

Hi! I'm Jonatan Schmidlechner, an almost-graduated master's student in computer science. This GitHub account is my portfolio showcasing various programming projects I've worked on. Below is a quick overview of the projects. Detailed information about each project can be found in its respective repository. The projects are sorted according to relevance, the top most projects are the most relevant.

## Featured Projects
- **[Competency management tool](https://github.com/ArtoKorpiharju/Osaamisenhallinta):** A web application (Spring Boot backend + React frontend + PostgreSQL database) developed for a private company for managing employee qualifications and competencies. Work still in progress. Belongs to the university's Software Engineering Project 2 (2026 Autumn). We had a team of 7 including 3 master students and 4 bachelor students.
  - I was the **Lead Backend Developer**, **Software Architect** & **Product owner**.
  - Scope: Solely responsible for designing and building the entire Spring Boot backend including the database from the ground up, operating independently without technical supervision or experienced (in spring boot) peers. Most of the backend code was written by me, while some of it was written by a bachelor student coached and supervised by me.
  - My contributions:
    - **System Design**: Architected the end-to-end software solution, creating the core domain model, ER diagrams, and component architecture spanning the frontend, REST controllers, services, and persistence layers.
    - **Backend Engineering**: Built a robust Spring Boot backend, serving as the primary developer and authoring the vast majority of the codebase. Utilized JPA/Hibernate for entity mapping, Flyway for database schema versioning and migrations, and REST API conventions.
    - **Technical Leadership**: Mentored a junior developer (bachelor student) by conducting technical onboarding for the Spring Boot framework, architecture and Mockito testing practices, and ensured code quality through regular PR reviews.
    - **Product Ownership**: Defined the core requirements and prevented scope creep to keep the MVP achievable. Reviewed each iteration of the UI mockups to verify that no planned features were missed.
    - **UI/UX Collaboration**: Reviewed iterative UI mockups and proposed concrete layout and workflow changes to improve usability and align the interface with the backend API.
- **[TRUE-MAS - A multi-agentic system for Terraform code generation](https://github.com/JonatanSchmidlechner/Multiagentic-system-for-IaC-generation):** A multi-agent AI system built in Python for synthesizing and validating AWS Terraform configurations from natural language prompts using Small Language Models (SLMs). Developed as my Master's thesis project at Tampere University (2026), building on top of the IaC-Eval benchmark framework.
    - I was the **Sole Developer** (developed under academic supervision).
    - **Scope:** Authored 100% of the codebase from the ground up—translating a high-level multi-agent concept (inspired by the MACOG architecture) into a working, reproducible system, including the agent orchestration pipeline, schema-grounding tools, automated validation and self-repair loop, and benchmarking harness for self-hosted models.
    - **My contributions:**
      - **Multi-Agent Architecture:** Engineered a four-agent pipeline (**Planner**, **Provider Harmonizer**, **IaC Generator**, and **Reviewer**) connected via typed Pydantic schemas (`PlannerPlan`, `IIRPlan`, `FixPlan`) to separate architectural planning, schema verification, HCL synthesis, and error repair.
      - **Schema Grounding & RAG:** Integrated **LlamaIndex** (RAG) retrieval over AWS Terraform documentation alongside a deterministic **AWS Provider Schema (`v5.75.0`)** lookup tool to supply candidate schemas, guiding the Provider Harmonizer agent to resolve planned components into exact AWS resource type names.
      - **Closed-Loop Self-Repair:** Integrated IaC-Eval's existing **Terraform CLI** (`plan`) and **Open Policy Agent (OPA / Rego)** validation checks into a bounded iterative repair loop, routing real compiler and policy error diagnostics back to the Reviewer agent for targeted HCL patches.
      - **Evaluation & Telemetry:** Extended the evaluation harness to track execution telemetry, plan accuracy, and Rego policy compliance across multiple agentic and prompt-engineering baselines.
- **[Moduuler (Youtube demo) - Kitchen component 3d editing tool](https://github.com/JonatanSchmidlechner/Moduuler-demo):**
  - Developed a 3D editor React component for a private company (npm package integration). Source code not publicly available. Check the video demo.
  - Completed in Spring 2024 as part of Software Project 1 course.
  - Demonstrates skills in TypeScript, React, and Redux slices, as well as the ability to quickly learn new technologies.
  - Showcases experience working in a small agile development team and applying software engineering best practices.
- **[Kubernetes submissions](https://github.com/JonatanSchmidlechner/-KubernetesSubmissions)** This repository was for course "Devops with Kubernetes". Here I deployed some dummy projects using local kubernetes clusters as well as Google Kubernetes Engine. During the course I learned a lot. Here are some areas that come to mind:
  - Container orchestration and scaling
  - Networking between containers
  - Automatic container recovery
  - Resource management (CPU & RAM requests/limits)
  - Rolling updates with zero downtime
  - Configuration and secret management
  - Github actions
- **[Personal project - Job Tracker (Unfinished)](https://github.com/JonatanSchmidlechner/jobTracker):** Job Tracker is a web app, which I started doing in my free time. The project mainly increased my confidence on web development skills I had already aqquired. Though, through this project I learned to implement a Firefox browser extension, which automatically (after a button press) extracts relevant information from a job posting and after a manual confirmation sends the data to a backend.
- **[Distributed systems - emoji data aggregator](https://github.com/JonatanSchmidlechner/Distributed-emoji-aggregator):** This project is a course project done in "Advanced web development: Back end" course Spring 2025. Its functionality is nothing special and it does not look that nice, however the focus of the project was to learn about microservice architecture and how to manage the communication between different containerized services. The application contains a simple frontend, two services of which the first one uses a REST API to communicate with the frontend, whereas the other one uses a websocket for real-time communication with the frontend. Additionally there is an emoji generator. The three backend components communicate with each other using apache kafka's messagebroker.
- **[Tram-car audio classifier](https://github.com/JonatanSchmidlechner/tram-car_audioClassifier):** This project is a machine learning based audio classifier for classifying new audiosamples either as car or tram. This is a smaller project done in a 2 person group in December 2024 for the course Introduction to audio and speech processing. This project demonstrates my basic audio processing knowledge with python as well as machine learning knowledge.
