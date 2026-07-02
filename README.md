## Hi there 👋

### Full-Stack Developer

I'm a full-stack developer building real-world web applications with **ASP.NET Core**, **Next.js**, **TypeScript**, and AI-powered product workflows.

I completed a **7–8 month volunteer internship**, where I gained hands-on experience with frontend/backend development, real project structures, debugging, and application workflows.

---

### Live Demo Project: Auranix

**Auranix** is my currently live demo project: a personalized product design platform where users can upload a photo, generate AI-powered visuals, and preview the result on products such as t-shirts, mugs, canvas prints, and magnets.

<a href="https://auranix.vercel.app/demo">
  <img src="./assets/tanitim.png" alt="Auranix Demo Preview" width="100%" />
</a>

**Live Demo:** https://auranix.vercel.app/demo

The current version runs as a demo without payment integration. Payment and checkout features are planned for a later production release.

Auranix uses **Next.js** on Vercel for the frontend, **ASP.NET Core** on Azure Container Apps for the backend, **PostgreSQL** for data, and **Cloudflare R2** for image and asset storage.

For the AI workflow, I did not use a ready-made paid image generation API. Instead, I deployed an **open-source AI model** on **Modal** to generate images with more control over the pipeline and better cost optimization.

For product previews, Auranix uses a separate **FastAPI + OpenCV rendering service** that places the generated image onto product mockups, adapting it to positioning, perspective, product surface, and t-shirt fold structure.

<details>
  <summary>More Auranix Preview</summary>

  <br />

  <img src="./assets/tanitim2.png" alt="Auranix Product Preview" width="100%" />
</details>

---

### Featured Projects

- **Auranix** — Personalized product design platform with self-deployed AI image generation, OpenCV mockup rendering, admin tools, cloud storage, and live demo deployment.
- **SmartVenue AI** — AI-powered business location analysis platform for evaluating competition, demographics, traffic, nearby demand, and location viability.
- **Social Media Automation** — Multi-platform dashboard for managing social media account connections, media uploads, and publishing workflows.
- **Learning Projects** — Practice projects and experiments built while improving my React, ASP.NET, and full-stack development skills.

---

### Focus Areas

ASP.NET Core, Next.js, TypeScript, PostgreSQL, MongoDB, FastAPI, Docker, Azure Container Apps, Vercel, Cloudflare R2, Modal, OpenCV, authentication, admin panels, image processing, and self-deployed AI workflows.
