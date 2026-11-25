# Mohammed Affan Khan

CS undergrad at PES University, Bengaluru (graduating 2027). I build AI workflows, agents and backend-heavy software, and I care about the parts that make them reliable: tests, human approval, safe defaults and clear architecture.

**Open to:** software engineering and applied AI internships and new-grad roles<br>
**Links:** [Portfolio](https://mohammed-affan-khan.vercel.app/) · [Resume](https://mohammed-affan-khan.vercel.app/resume) · [LinkedIn](https://www.linkedin.com/in/md-affan-khan-960783306/) · [Email](mailto:mdaffankhan7910@gmail.com)

---

## What I'm building now

These repositories are private. I'm happy to walk through the code or give a demo.

### Voxlead: AI workflow for sales enquiries *(solo · in development)*
Takes in a building-material dealer's enquiries, replies on WhatsApp, works out what the buyer needs, drafts a quote and schedules follow-ups.

- **The AI never sets a price.** Claude turns the chat into a structured requirement, and plain code calculates the quote from the dealer's catalog
- A person approves every quote, and a draft-only mode lets a dealer try it without messaging a real buyer
- Multi-tenant: each business's data is separated by database access rules
- 764 automated tests, plus an evaluation set for requirement extraction
- **Stack:** Next.js, TypeScript, Supabase/Postgres, WhatsApp Cloud API, Claude API

### Nova: local-first personal AI agent *(owner · two-person project · active)*
Plans tasks, carries them out step by step, keeps progress across restarts, and asks for approval before anything consequential.

- Runs on local models through Ollama, with a durable task journal, crash recovery and owner-controlled memory
- Research tools store every source and treat web text as untrusted data
- 370+ tests, GitHub Actions CI and design decisions recorded as ADRs
- Nova's own Python layer sits on the open-source [OpenJarvis](https://github.com/open-jarvis/OpenJarvis) framework, included in the repository
- **Stack:** Python, SQLite, Ollama

### Agent Hub: workflow for coding with two AI agents *(solo · in daily use)*
Routes my development work between Claude Code and Codex and enforces the rules around it.

- Picks a route by task difficulty and an agent by remaining allowance, with cross-agent review before merging
- A merge guard blocks merges with failing checks, open review threads or missing owner approval (221 test cases)
- An hourly, read-only inbox workflow that finds deadlines and renewals, with checks that catch searches that fail silently
- **Stack:** Bash, Python, Next.js, Postgres, macOS launchd

### IntelliHome: AI house-design pipeline *(team capstone · active)*
Turns a conversation about requirements into rule-checked floor plans, drawings and 3D models.

- Team project in a private repository owned by a teammate
- My work includes error handling, code-quality checks, the electrical and plumbing sheets, STL/GLB export and the chat-first frontend redesign
- **Stack:** Python, FastAPI, OR-Tools, Shapely, React

> Voxlead, Nova, Agent Hub and IntelliHome are built with AI coding agents (Claude Code and Codex).

---

## Public projects

| Project | What it is | Stack |
|---|---|---|
| [**ProConnect**](https://github.com/MohammedAffanKhan779/Professional-Networking) | LinkedIn-style platform: profiles, feed, connections with mutual suggestions, comments and likes, resume builder. MySQL triggers keep like and comment counts consistent. JWT auth. | React, TypeScript, Vite, Tailwind, Node/Express, MySQL |
| [**Disaster Relief Management**](https://github.com/MohammedAffanKhan779/Disaster-Relief-Management-System) | Role-based relief operations: events, relief centers, resource allocation, donations, reports and dashboards, plus a REST API. CI builds on every push to main. | Java 21, Spring Boot 3, JPA, Thymeleaf, MySQL, GitHub Actions |
| [**Jenkins + Docker load balancing**](https://github.com/MohammedAffanKhan779/PES2UG23CS343_Jenkins) | Jenkins pipeline that builds a Dockerized backend, runs two replicas and fronts them with an Nginx load balancer. | Jenkins, Docker, Nginx |
| [**ROS2 fire-detection drone**](https://github.com/Shehzaad-khan/drone-fire-detection-ros2) *(team)* | Simulated patrol drone in Gazebo that detects fire and raises alerts. I wrote the initial OpenCV fire-detection node ([commit 7f76c39](https://github.com/Shehzaad-khan/drone-fire-detection-ros2/commit/7f76c39)), later refined by teammates. | ROS2, Python, OpenCV |
| [**Kafka-style message broker**](https://github.com/NavneetNayak/90_Project2_BD) *(team)* | Leader/follower broker with producers and consumers. I wrote the producer. | Python |

**Coursework:** [GenAI hands-on](https://github.com/MohammedAffanKhan779/GenAI_Handson) (LangChain, prompt engineering) · [ML labs](https://github.com/MohammedAffanKhan779/ML_F_PES2UG23CS343_Mohammed_Affan_Khan) (decision trees in scikit-learn and PyTorch) · [Cloud monolith lab](https://github.com/MohammedAffanKhan779/Cloud_Computing-MONOLITHIC-ARCHITECTURE) (Locust load tests)

---

## Stack

**Languages:** Python, TypeScript, JavaScript, Java, SQL<br>
**AI:** Claude API, Ollama, LangChain, agent workflows, evaluation sets, scikit-learn, PyTorch, OpenCV<br>
**Backend:** Node/Express, Spring Boot, FastAPI, Supabase/Postgres, MySQL<br>
**Frontend:** React, Next.js, Vite, Tailwind<br>
**Infra:** GitHub Actions, Docker, Jenkins, Nginx, Vercel, Linux
