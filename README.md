# 🚀 David Parra | Full-Stack Software Developer Portfolio

Welcome to the repository of my personal portfolio. Built with modern web technologies, this project reflects my expertise in full-stack software development, database consulting, clean user interfaces, and robust deployment pipelines.

<p align="center">
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge" alt="Status" />
  <img src="https://img.shields.io/badge/Next.js-16-black?style=for-the-badge&logo=next.js" alt="Next.js" />
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
</p>

---

## 🛠️ Tech Stack & Expertise

This portfolio leverages industry-standard tools to guarantee maximum performance, strict type safety, and a seamless user experience:

*   **Core Framework:** [Next.js](https://nextjs.org/) (App Router) for hybrid rendering and optimal routing.
*   **Language:** [TypeScript](https://www.typescriptlang.org/) for robust, type-safe application logic.
*   **Styling:** [Tailwind CSS](https://tailwindcss.com/) for modern, responsive, mobile-first design systems.
*   **Backend & Databases:** Experience spanning Spring Boot, FastAPI, Oracle Cloud Infrastructure (OCI), PostgreSQL, and MySQL.
*   **Containerization:** Multi-stage **Docker** builds (`standalone` output) ensuring secure production isolation.

---

## 📂 Project Structure

```text
├── src/
│   ├── app/           # App Router pages, layouts, and routing logic
│   ├── components/    # Reusable UI components and layout sections
│   └── styles/        # Global stylesheets and configuration assets
├── public/            # Static assets (images, icons, vectors)
├── Dockerfile         # Multi-stage production container configuration
├── next.config.ts     # Next.js configuration (Standalone output enabled)
└── package.json       # Project dependencies and operational scripts
```

---

## ⚙️ Getting Started Locally
To run this project on your local environment, follow these steps:

* **Clone the repository:**

```bash
git clone [https://github.com/Dragetsus/portafolio.git](https://github.com/DavidRParra/Portafolio)
cd portafolio
```

* **Install dependencies:**


```bash
npm install
```

* **Run the development server:**


```bash
npm run dev
```
Open http://localhost:3000 with your browser to see the result.

## 🐳 Docker Production Build

The project includes a production-ready Dockerfile structured to isolate the environment securely under non-root configurations. To build and run it locally:

```bash
# Build the Docker image
docker build -t portfolio-app .


# Run the container on port 3000
docker run -p 3000:3000 portfolio-app
```

---

## 📬 Connect & Collaborate

* **GitHub:** [@DavidRParra](https://github.com/DavidRParra)
* **Alias:** David Parra

---
Designed and engineered with 💙 and clean code by David Parra.
