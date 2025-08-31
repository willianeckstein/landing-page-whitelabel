# Landing Page White-Label

> 🚀 Modern, reusable, and high-performance landing page base built with **Next.js 15**, **React 19**, **TypeScript 5**, and **TailwindCSS 4**.  
> Focused on best practices for **architecture, accessibility, SEO, and performance**.  

---

## ✨ Purpose

This project serves as a **white-label template** for building landing pages:
- Reusable in real-world projects.
- Configured with **advanced type-checking**.
- Ready for **CI/CD** and quality verification.
- A foundation for learning and deepening technical skills at an advanced level.

---

## 📂 Project Structure
```
├── .github/workflows/   # CI workflows
├── src/                 # source code
│   └── app/             # Next.js App Router routes
├── tsconfig.json        # TypeScript config for development
├── tsconfig.ci.json     # stricter TypeScript config for CI
├── package.json
└── README.md
```

---

## ⚙️ Scripts

| Command                | Description                                                               |
|-------------------------|---------------------------------------------------------------------------|
| `npm run dev`          | Starts the development server.                                            |
| `npm run build`        | Builds the production bundle.                                             |
| `npm start`            | Runs the app in production mode.                                          |
| `npm run lint`         | Runs lint checks (Next + ESLint).                                         |
| `npm run type-check`   | Local type-check (fast, skips third-party libraries).                     |
| `npm run type-check:ci`| CI type-check (strict, validates third-party libraries as well).           |
| `npm run clean:ts`     | Removes caches and `.tsbuildinfo` files.                                  |

---

## 🧰 Tech Stack

- [Next.js 15 (App Router)](https://nextjs.org/)
- [React 19](https://react.dev/)
- [TypeScript 5](https://www.typescriptlang.org/)
- [TailwindCSS 4](https://tailwindcss.com/)
- [ESLint 9 + eslint-config-next](https://eslint.org/)

---

## 🔒 Quality & CI

- **TypeScript** with strict flags (`exactOptionalPropertyTypes`, `noUncheckedIndexedAccess`, etc).
- **Separate scripts** for local vs CI checks.
- **GitHub Action** to run type-checking on every `push`/`PR`.
- `.nvmrc` file to ensure consistent Node.js version.

---

## 🚀 Getting Started

1. Clone the repository:
```bash
git clone https://github.com/sua-org/landing-page-whitelabel.git
cd landing-page-whitelabel
```

2.	Set Node.js version according to .nvmrc:
```bash
nvm use
```

3.	Install dependencies:
```bash
npm install
```

4.	Run in development mode:
```bash
npm run dev
```

## 📜 License

MIT © Willian Eckstein
Free to use responsibly.
