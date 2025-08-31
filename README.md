# Landing Page White-Label

> 🚀 Base de landing page moderna, reutilizável e de alta performance, criada com **Next.js 15**, **React 19**, **TypeScript 5** e **TailwindCSS 4**.  
> Focada em boas práticas de **arquitetura, acessibilidade, SEO e performance**.  

---

## ✨ Objetivo

Este projeto serve como **template white-label** para construção de landing pages:
- Reutilizável em projetos reais.
- Configurado com **type-checking avançado**.
- Preparado para **CI/CD** e verificação de qualidade.
- Base para estudos e aprofundamento técnico em nível avançado.

---

## 📂 Estrutura Inicial
```
├── .github/workflows/   # actions de CI
├── src/                 # código fonte
│   └── app/             # rotas do Next.js (App Router)
├── tsconfig.json        # config TS para dev
├── tsconfig.ci.json     # config TS mais rígida para CI
├── package.json
└── README.md
```

---

## ⚙️ Scripts

| Comando                | Descrição                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| `npm run dev`          | Inicia servidor de desenvolvimento.                                       |
| `npm run build`        | Gera build de produção.                                                   |
| `npm start`            | Roda servidor em produção.                                                |
| `npm run lint`         | Executa lint (Next + ESLint).                                             |
| `npm run type-check`   | Checagem de tipos local (rápida, ignora libs de terceiros).                |
| `npm run type-check:ci`| Checagem de tipos em modo CI (rígida, valida libs também).                 |
| `npm run clean:ts`     | Remove caches e arquivos `.tsbuildinfo`.                                  |

---

## 🧰 Tecnologias

- [Next.js 15 (App Router)](https://nextjs.org/)
- [React 19](https://react.dev/)
- [TypeScript 5](https://www.typescriptlang.org/)
- [TailwindCSS 4](https://tailwindcss.com/)
- [ESLint 9 + eslint-config-next](https://eslint.org/)

---

## 🔒 Qualidade & CI

- **TypeScript** com flags estritas (`exactOptionalPropertyTypes`, `noUncheckedIndexedAccess`, etc).
- **Scripts separados** para checagem local vs CI.
- **GitHub Action** para rodar type-checking em todo `push`/`PR`.
- Arquivo `.nvmrc` para garantir versão de Node consistente.

---

## 🚀 Como usar

1. Clone o repositório:
```bash
git clone https://github.com/sua-org/landing-page-whitelabel.git
cd landing-page-whitelabel
```

2.	Configure o Node conforme .nvmrc:
```bash
nvm use
```

3.	Instale as dependências:
```bash
npm install
```

4.	Rode em desenvolvimento:
```bash
npm run dev
```

## 📜 Licença

MIT © Willian Eckstein
Use livremente, com responsabilidade.
