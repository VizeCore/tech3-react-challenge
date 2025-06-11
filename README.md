# 🚀 Desafio Front-End – React + TypeScript · **Aiva**

Olá dev! 👋  
Nós da **Aiva** queremos ver **seu jeito** de escrever código, estruturar projetos e entregar valor.  
A missão é simples: montar uma mini-app que consuma **uma das APIs abaixo** e publicar tudo no GitHub + deploy gratuito.

---

## 1. Escolha sua API

| API | Quando usar | Endpoints legais |
|-----|-------------|------------------|
| **Fake Store API** | Quer algo “e-commerce style” (produtos, categorias, usuários…). | `/products`, `/categories`, `/users`, `/carts` |
| **DEV.to (Forem) API** | Prefere um mini-blog/CMS (posts, rascunhos, tags, comentários). | `/articles`, `/drafts`, `/tags`, `/comments` |

> **DEV.to** exige uma API Key (crie em Settings).  
> Headers obrigatórios:  
> `api-key: YOUR_KEY`  
> `accept: application/vnd.forem.api-v1+json`

---

## 2. O que sua app precisa ter ⚙️

Os itens abaixo são **guidelines**. Ajuste o escopo conforme a API escolhida – o importante é mostrar domínio de boas práticas:

- **Fluxo de autenticação** caso a API suporte (login, registro ou uso de token).  
- **Dashboard principal** com **listagem**, **busca** e/ou **filtros** relevantes.  
- **Operações de CRUD** (criar, editar, remover) para pelo menos um recurso-chave.  
- **Página de detalhe** para um item individual.  
- **Responsividade** e feedback visual (loading, estados vazios, erros).  

Sinta-se livre para adicionar features extras que valorizem a usabilidade ou demonstrem seu conhecimento.

---

## 3. Stack (mínimo obrigatório)

| Item | Requisito |
|------|-----------|
| **Linguagem** | TypeScript |
| **Framework/Bundler** | **Vite** **ou** **Next.js** – explique no README por que escolheu 😉 |
| **UI** | Livre (MUI, Chakra, Tailwind, CSS-in-JS…) |
| **Estado/Dados** | React Query, SWR, Redux Toolkit, Zustand… à sua escolha |
| **Roteamento** | React Router (Vite) ou App/Pages Router (Next) |
| **Testes** | Jest + Testing Library **e** pelo menos 1 E2E (Cypress/Playwright) |
| **Qualidade** | ESLint + Prettier, Husky/lint-staged, commits semânticos |
| **Deploy** | Vercel, Netlify, Render, Railway… versão grátis tá ótimo |

---

## 4. Extras pra brilhar ✨

- Code splitting & lazy loading  
- Web Vitals e otimização de imagens  
- Design System/componentes reutilizáveis
- Documentação clara no **README.md**
- CI GitHub Actions (lint, build, testes)
---

## 5. Como entregar 📦

1. Repositório **público** no GitHub com todo o código.  
2. **README caprichado**: setup, scripts, `.env.example`, arquitetura, link de produção, motivo do Vite/Next.  
3. URL do **deploy** funcionando.

⏰ **Prazo de entrega**: 18/06/2025 23:59.  
Quando terminar, envie o link do repo + deploy.

Boa sorte — e divirta-se!  
*Equipe Aiva* 😄
