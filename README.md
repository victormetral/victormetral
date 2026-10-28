# Bonjour, je suis Victor 👋

**Développeur fullstack en reconversion — orientation DevOps**

- 🎯 Je recherche une **alternance de 12 mois**, démarrage **janvier ou février 2027**
- 📍 Lyon — **full remote** ou mobilité France entière
- 🎹 Ancien pianiste concertiste international

---

## Mon parcours

Pendant quinze ans, j'ai été pianiste concertiste : plus de 500 concerts en France et à l'international, cinq albums, plusieurs distinctions internationales.

Ce métier m'a appris trois choses qui servent tous les jours en développement : travailler seul pendant des mois sur un objectif lointain, livrer à la date prévue quoi qu'il arrive, et rester lucide sous pression.

Je me forme aujourd'hui chez **Ada Tech School** (Lyon) et je prépare le titre **Concepteur développeur d'applications, RNCP niveau 6 (Bac+3/4)**, à valider en alternance à partir de janvier 2027.

---

## Ce sur quoi je travaille en ce moment

Trois chantiers en parallèle, chacun sur un axe différent.

**Concevoir** — [financepilot](https://github.com/victormetral/financepilot), mon projet du titre RNCP. Refonte complète en repartant du besoin : utilisateurs interrogés, 38 user stories priorisées, modèle de données en trois niveaux, architecture décidée et écrite avant le code.

**Exploiter** — [orchestra](https://github.com/victormetral/orchestra), ma plateforme de production personnelle, plus la spé DevOps / Opérations et Sécurité. Conteneurs, reverse proxy, supervision, et bientôt CI/CD et cloud. Une demi-heure par jour, une pull request par séance.

**Élargir** — [polyglotte](https://github.com/victormetral/polyglotte), où j'apprends TypeScript, PHP, Java et Python en parallèle, notion par notion, pour raisonner en concepts plutôt qu'en syntaxe.

---

## Mes projets

### 🧭 [financepilot](https://github.com/victormetral/financepilot) — projet du titre RNCP 6

`TypeScript` · `NestJS` · `PostgreSQL` · `Prisma` · `React`

Application de finances personnelles : voir tous ses comptes au même endroit, **sans connecter sa banque**. Les données entrent par saisie manuelle ou import de relevés PDF lus dans le navigateur.

Ce dépôt documente la démarche autant que le code : 38 user stories estimées et priorisées, modèle de données conçu avant les tables, et un [ADR](https://github.com/victormetral/financepilot/blob/main/docs/adr/0001-architecture-de-base.md) qui compare quatre architectures avant d'en retenir une — client-serveur, back en couches — avec les conséquences assumées.

> Conception terminée, socle technique en cours. Le code qui tourne est dans v0 ci-dessous.

### 🏦 [financepilot-v0](https://github.com/victormetral/financepilot-v0) — la première version, fonctionnelle

`React` · `Node.js` · `Express` · `PostgreSQL` · `Docker`

Comptes, transactions, budgets, objectifs d'épargne et transactions récurrentes. Génération idempotente des échéances, sans tâche planifiée. **59 tests unitaires et 5 scripts d'intégration** exécutés à chaque envoi de code.

Sécurité applicative : cookie `httpOnly`, helmet, CORS restreint, limitation de requêtes, requêtes paramétrées.

### 🎼 [orchestra](https://github.com/victormetral/orchestra) — plateforme de production personnelle

`Docker` · `Docker Compose` · `Caddy` · `Uptime Kuma` · `Linux`

Mes autres projets montrent que je sais **construire** des applications. Celui-ci montre que je sais les **faire tourner** : déployer, superviser, sécuriser, et réparer quand ça casse.

Trajectoire en sept phases, du local au VPS puis au cloud. Chaque choix structurant est consigné dans un ADR, chaque séance donne une branche et une pull request.

### 🐳 [defi-dockerfile](https://github.com/victormetral/defi-dockerfile) — conteneurisation et sécurité

`Docker` · `Node.js`

Conteneuriser une application sans la connaître à l'avance. Le [rapport](https://github.com/victormetral/defi-dockerfile/blob/main/RAPPORT.md) détaille l'enquête préalable — version du runtime, fichiers réellement nécessaires, dépendances d'exécution — puis chaque choix et les alternatives écartées.

Résultat : image sans dépendance inutile, aucun secret embarqué, application lancée avec un utilisateur non privilégié.

Voir aussi [defi-reseau-rapport](https://github.com/victormetral/defi-reseau-rapport) : six défis réseau documentés, de l'adressage aux ports exposés.

### 🎹 [polyglotte](https://github.com/victormetral/polyglotte) — un concept, quatre langages

`TypeScript` · `PHP` · `Java` · `Python` · `React` · `Linux`

Chaque notion est travaillée dans les quatre langages à la suite, avec une étude React et un exercice Linux. L'idée : voir ce qui est un vrai concept et ce qui n'est qu'une particularité de syntaxe.

### 🗺️ [devparis-radar-react](https://github.com/victormetral/devparis-radar-react) — démo en ligne

`React` · `Vite` · `Leaflet`

Exploration des lieux tech de Paris via l'API OpenData : recherche, filtres, pagination, carte interactive. Tests Vitest, accessibilité ARIA.

👉 **[Voir la démo](https://devparis-radar-react.netlify.app)**

---

**Autres projets de formation** : [todo-app](https://github.com/victormetral/todo-app) (application conteneurisée avec pipeline CI/CD), [adapi](https://github.com/victormetral/adapi) (API REST documentée avec Swagger), [adatabase](https://github.com/victormetral/adatabase) (base de données relationnelle modélisée en Merise).

---

## Compétences

**Je les utilise aujourd'hui**

- **Frontend** — React, JavaScript ES6+, Vite, HTML5, CSS3, responsive
- **Backend** — Node.js, Express, API REST, authentification JWT, architecture en couches, Swagger
- **Données** — PostgreSQL, SQL sans ORM, modélisation relationnelle (Merise, UML), migrations réversibles
- **Conteneurs et CI/CD** — Docker, Docker Compose, GitHub Actions, GitHub Container Registry, Linux
- **Tests** — Vitest, Jest, Playwright, scripts d'intégration bash
- **Sécurité applicative** — cookie httpOnly, helmet, CORS restreint, limitation de requêtes, requêtes paramétrées
- **Méthode** — Git, pull requests, ADR, user stories, sprints

**Je les apprends en ce moment**

TypeScript, NestJS, Prisma, PHP, Java, Python, reverse proxy et supervision.

**Mes prochaines étapes** — cloud, infrastructure as code, Kubernetes, cybersécurité. Ce ne sont pas encore des acquis, et je préfère le dire.

---

## Ce que je cherche

Une alternance où je code vraiment, avec du monde autour de moi :

- une **équipe technique structurée** et un **tuteur disponible**
- des **revues de code** — c'est ce qui me fera progresser le plus vite
- du **full remote** ou de l'hybride, partout en France

Une équipe qui m'apprend sa technologie m'intéresse autant qu'une équipe qui utilise déjà la mienne.

**Le cadre pratique**

- **Rythme** — 4 jours en entreprise, le vendredi en formation, plus 3 semaines de séminaire dans l'année
- **Contrat** — professionnalisation, 12 mois
- **Démarrage** — janvier ou février 2027

---

## Me contacter

- 📧 victor.metral@gmail.com
- 💼 [LinkedIn](https://linkedin.com/in/victor-metral-dev)

---

<details>
<summary><b>🇬🇧 English version</b></summary>

<br>

## Hi, I'm Victor 👋

**Career-changing fullstack developer — DevOps oriented**

- 🎯 Looking for a **12-month apprenticeship** in France, starting **January or February 2027**
- 📍 Based in Lyon — **fully remote** or open to relocation within France
- 🎹 Former international concert pianist

### Background

For fifteen years I was a concert pianist: over 500 concerts in France and abroad, five albums, several international awards.

That career taught me three things I use every day as a developer: working alone for months toward a distant goal, delivering on the agreed date no matter what, and staying clear-headed under pressure.

I'm now training at **Ada Tech School** (Lyon), preparing a French RNCP level 6 qualification (equivalent to a Bachelor's degree) in application design and development, to be completed through an apprenticeship starting January 2027.

### What I'm working on

Three parallel tracks, each on a different axis.

**Designing** — [financepilot](https://github.com/victormetral/financepilot), my qualification project. A full rewrite starting from user needs: interviews, 38 prioritised user stories, a three-level data model, and the architecture decided and written down before any code.

**Operating** — [orchestra](https://github.com/victormetral/orchestra), my personal production platform, alongside a DevOps / Operations & Security specialisation. Containers, reverse proxy, monitoring, then CI/CD and cloud. Half an hour a day, one pull request per session.

**Broadening** — [polyglotte](https://github.com/victormetral/polyglotte), learning TypeScript, PHP, Java and Python in parallel, concept by concept.

### Projects

- **[financepilot](https://github.com/victormetral/financepilot)** — personal finance app, **no bank connection**: manual entry or PDF statement import parsed in the browser. The repository documents the method as much as the code: 38 estimated user stories, a data model designed before the tables, and an [ADR](https://github.com/victormetral/financepilot/blob/main/docs/adr/0001-architecture-de-base.md) comparing four architectures before settling on a layered client-server design. TypeScript, NestJS, PostgreSQL, Prisma, React. *Design complete, technical foundation in progress.*
- **[financepilot-v0](https://github.com/victormetral/financepilot-v0)** — the first, working version. Accounts, transactions, budgets, savings goals and recurring transactions with idempotent scheduling. **59 unit tests and 5 integration scripts** running on every push. React, Node.js, Express, PostgreSQL, Docker.
- **[orchestra](https://github.com/victormetral/orchestra)** — personal production platform. My other projects show I can *build* applications; this one shows I can *run* them. Seven phases from local to VPS to cloud, every structural choice recorded as an ADR.
- **[defi-dockerfile](https://github.com/victormetral/defi-dockerfile)** — containerising an unfamiliar application. The [report](https://github.com/victormetral/defi-dockerfile/blob/main/RAPPORT.md) covers the investigation, each decision and the rejected alternatives. No unnecessary dependencies, no embedded secrets, non-root execution. See also [defi-reseau-rapport](https://github.com/victormetral/defi-reseau-rapport): six documented networking challenges.
- **[polyglotte](https://github.com/victormetral/polyglotte)** — one concept, four languages, plus a React étude and a Linux exercise each time. Telling real concepts apart from mere syntax.
- **[devparis-radar-react](https://github.com/victormetral/devparis-radar-react)** — Paris tech venues explorer built on OpenData: search, filters, pagination, interactive map. Vitest tests, ARIA accessibility. [Live demo](https://devparis-radar-react.netlify.app)

*Other training projects*: [todo-app](https://github.com/victormetral/todo-app) (containerised app with a CI/CD pipeline), [adapi](https://github.com/victormetral/adapi) (REST API documented with Swagger), [adatabase](https://github.com/victormetral/adatabase) (relational database modelled with Merise).

### Skills

**Using today**

- **Frontend** — React, JavaScript ES6+, Vite, HTML5, CSS3, responsive
- **Backend** — Node.js, Express, REST APIs, JWT authentication, layered architecture, Swagger
- **Data** — PostgreSQL, raw SQL, relational modelling, reversible migrations
- **Containers and CI/CD** — Docker, Docker Compose, GitHub Actions, GitHub Container Registry, Linux
- **Testing** — Vitest, Jest, Playwright, bash integration scripts
- **Application security** — httpOnly cookies, helmet, restricted CORS, rate limiting, parameterised queries
- **Method** — Git, pull requests, ADRs, user stories, sprints

**Learning right now** — TypeScript, NestJS, Prisma, PHP, Java, Python, reverse proxies and monitoring.

**Next** — cloud, infrastructure as code, Kubernetes, cybersecurity. Not skills yet, and I'd rather say so.

### What I'm looking for

An apprenticeship where I actually write code, surrounded by people I can learn from:

- a **structured technical team** and an **available mentor**
- **code reviews** — the fastest way for me to improve
- **fully remote** or hybrid, anywhere in France

A team that teaches me its own stack interests me as much as one already using mine.

**Practical details**

- **Schedule** — 4 days in the company, Fridays at school, plus 3 seminar weeks per year
- **Contract** — 12-month French apprenticeship (*contrat de professionnalisation*)
- **Start** — January or February 2027

### Get in touch

- 📧 victor.metral@gmail.com
- 💼 [LinkedIn](https://linkedin.com/in/victor-metral-dev)

</details>
