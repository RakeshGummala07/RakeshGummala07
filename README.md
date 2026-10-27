```
██████╗  █████╗ ██╗  ██╗███████╗███████╗██╗  ██╗
██╔══██╗██╔══██╗██║ ██╔╝██╔════╝██╔════╝██║  ██║
██████╔╝███████║█████╔╝ █████╗  ███████╗███████║
██╔══██╗██╔══██║██╔═██╗ ██╔══╝  ╚════██║██╔══██║
██║  ██║██║  ██║██║  ██╗███████╗███████║██║  ██║
╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝╚══════╝╚══════╝╚═╝  ╚═╝
```

**Rakesh Gummala** &nbsp;/&nbsp; Backend & Full-Stack Developer &nbsp;/&nbsp; Hyderabad, India

> [!NOTE]
> Open to entry-level SDE roles: Java, Spring Boot, microservices.

[LinkedIn](https://www.linkedin.com/in/rakesh-gummala-24873736b) &nbsp;/&nbsp; [Email](mailto:rakeshgummala7@gmail.com) &nbsp;/&nbsp; [Portfolio](https://www.rakeshgummala.vercel.app) &nbsp;/&nbsp; [LeetCode](https://leetcode.com/u/Rakesh_Gummala/)

---

### $ whoami

```console
$ whoami
rakesh-gummala

$ cat profile.txt
role        Backend & Full-Stack Developer
education   B.Tech ECE '26, Sree Chaitanya College of Engineering
location    Hyderabad, India
focus       microservices, event-driven design, RAG and vector search
practice    DSA in Java (200+ LeetCode), HLD / LLD, Docker-first debugging

$ cat status.txt
building    Projects
looking     entry-level SDE roles
```

---

### $ tree devmind/

AI-powered developer intelligence platform: chat with a codebase, get AI-assisted pull request reviews, generate documentation, and track engineering analytics. [View the repo.](https://github.com/RakeshGummala07/DevMind)

```console
devmind/
├── api-gateway             routing, JWT validation
├── auth-service            JWT, rotating refresh tokens, GitHub OAuth2
├── repository-service      GitHub repository connection
├── ingestion-service       Chunking, embeddings
├── ai-service              RAG chat, PR review, doc generation
├── analysis-service        Engineering analytics
├── notification-service    Kafka fan-out
└── frontend                React, Redux Toolkit, TanStack Query
```

```console
$ cat devmind/infra.txt
messaging   Kafka (KRaft)
data        MySQL + Flyway, MongoDB, Qdrant
llm         Ollama, self-hosted
devops      Docker Compose, Kubernetes, Grafana, GitHub Actions CI/CD to GHCR
```

---

### $ ls projects/

```console
educollab/              Educational collaboration platform, monolith migrated to microservices.
                        Auth, profiles, enrollment, feed, chat, notifications, meetings, admin, AI.
                        Java 21, Spring Boot 3, Kafka, Redis, React, LiveKit, Spring AI + Qdrant

stayomi/                Hotel management app, deployed on Render with GitHub Actions CI/CD.
                        JavaScript

microservices-nodejs/   Social media backend as Node.js microservices.
                        RabbitMQ, Redis, Cloudinary

my-portfolio/           Responsive portfolio site.
                        React, Tailwind CSS
```

[Stayomi](https://github.com/RakeshGummala07/Stayomi) &nbsp;/&nbsp; [Microservices-Node.js](https://github.com/RakeshGummala07/Microservices-Node.js) &nbsp;/&nbsp; [My-Portfolio](https://github.com/RakeshGummala07/My-Portfolio)

<!-- Link EduCollab here once the repo is public: [EduCollab](https://github.com/RakeshGummala07/YOUR-EDUCOLLAB-REPO) -->

---

### $ cat stack.json

```json
{
  "languages": ["Java", "JavaScript", "Python", "SQL"],
  "backend":   ["Spring Boot", "Spring Cloud Gateway", "Spring AI", "Node.js", "Kafka", "RabbitMQ"],
  "data":      ["MySQL", "MongoDB", "Redis", "Qdrant", "Flyway"],
  "frontend":  ["React", "Redux Toolkit", "TanStack Query", "Tailwind CSS", "Vite"],
  "devops":    ["Docker", "Kubernetes", "GitHub Actions", "Grafana", "Maven", "Git"],
  "concepts":  ["DSA", "HLD / LLD", "REST API design", "JWT / OAuth2", "RAG"]
}
```

---

### $ tail -f debug.log

<details>
<summary>Real problems I've debugged while building EduCollab (click to expand)</summary>

```log
[ERROR] NoSuchMethodError                      spring-cloud-gateway
[FIX  ] version incompatibility, upgraded to Spring Boot 3.3.6

[ERROR] service-to-service requests rejected   jwt across services
[FIX  ] branch on service tokens vs. user tokens

[ERROR] LazyInitializationException            entity accessed outside a session
[FIX  ] corrected fetching and transaction boundaries

[ERROR] duplicate joins under load             concurrent join calls
[FIX  ] resolved the race condition

[ERROR] containers dropping off the network    docker on WSL2
[FIX  ] rebuilt only the affected services instead of restarting the whole stack
```

</details>

---

### $ ./contact.sh

```console
$ ./contact.sh
Hiring for an entry-level SDE role, or want to talk microservices?
```

[LinkedIn](https://www.linkedin.com/in/rakesh-gummala-24873736b) &nbsp;/&nbsp; [Email](mailto:rakeshgummala7@gmail.com)

```console
$ exit 0
```
