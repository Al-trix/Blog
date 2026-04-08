# 📚 English Class Evidence Blog — Álvaro Arboleda Marulanda

A personal blog built with **Astro + Tailwind CSS** to document and present the evidence gathered throughout my English language course. The site showcases written work, multimedia content, emails, chronicles, and other class activities in a clean, modern interface.

---

## 🗂️ Sections

| Section         | Description                                                   |
| --------------- | ------------------------------------------------------------- |
| **Posts**       | Reflective blog posts and opinion articles written in English |
| **Evidencia 1** | Chronicle and written narratives from class activities        |
| **Evidencia 2** | Email composition and formal writing exercises                |
| **Multimedias** | Maps, group photos, and visual media from class               |
| **Extras**      | Additional supporting materials (flyers, brochures, etc.)     |

---

## 🚀 Tech Stack

- [Astro](https://astro.build) — Static site generator
- [Tailwind CSS v4](https://tailwindcss.com) — Utility-first styling
- [React](https://react.dev) — Used for interactive island components
- [Heroicons](https://heroicons.com) — SVG icon library

---

## 🧞 Commands

Run from the root of the project:

| Command        | Action                               |
| -------------- | ------------------------------------ |
| `pnpm install` | Install dependencies                 |
| `pnpm dev`     | Start dev server at `localhost:4321` |
| `pnpm build`   | Build for production to `./dist/`    |
| `pnpm preview` | Preview production build locally     |

---

## 📁 Project Structure

```text
/
├── public/
│   └── favicon.svg
└── src/
    ├── components/
    │   ├── evidences/
    │   │   ├── evidence1/      # Chronicle & written evidence
    │   │   ├── evidence2/      # Email evidence
    │   │   ├── multimedia/     # Photos & maps
    │   │   └── evidencesExtras/# Extra materials
    │   ├── Header.astro
    │   ├── Nav.astro
    │   ├── Post.astro
    │   └── Posts.astro
    ├── layouts/
    │   └── Layout.astro
    ├── pages/
    │   └── index.astro
    └── styles/
        └── global.css
```
