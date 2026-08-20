<div align="center">

# CV — Bruno Roberto Santos

<img src="profile/me.png" alt="Bruno Roberto Santos" width="160" />

Currículo em LaTeX, disponível em português e inglês, compilado em PDF.

**Engenheiro de Software (Full-Stack)** com 5+ anos de experiência em React, Next.js, Node.js/NestJS e migração de sistemas legados para stacks modernas.

📧 [contato@brunorobertosantos.com.br](mailto:contato@brunorobertosantos.com.br)
📞 [(35) 91023-6179](tel:+5535910236179)
📍 Alfenas/MG
🔗 [LinkedIn](https://www.linkedin.com/in/rsbruno/) · [GitHub](https://github.com/rsbruno) · [Portfólio](https://brunorobertosantos.com.br/)

## Sobre

Atuei quase 3 anos em squad de 40+ pessoas na GlobalSys (Grupo Águia Branca, Projeto Lets). Hoje sigo fullstack no Inteli e em projetos de cliente na Bitway, onde arquitetei migrações de sistemas legados para stacks modernas, atingindo até 100 SEO e 90+ desempenho no Lighthouse. Já desenvolvi frontend para plataforma do Governo Federal. Participo de programa de parceiros com **Anthropic** e **OpenAI**, estudando aplicações com IA.

## Experiência

- **Inteli** — Engenheiro de Software Fullstack (Pleno/Sênior) · Fev 2026 – Atual
  Sistema acadêmico (React, Node.js/Express, AWS Lambda, Aurora/MySQL); criei o módulo de intercâmbio e o módulo de restrições de alunos/chamados.
- **Trocafone** — Engenheiro de Software Fullstack (Pleno) · Out 2025 – Jul 2026
  Migração PHP/Laravel → Next.js no Trocafácil (100 SEO / 90 desempenho / 91 acessibilidade no Lighthouse); modernização PHP+Angular → Vite.js + TanStack; 2 produtos internos do zero (Integr8 e Polly).
- **GlobalSys / Grupo Águia Branca** — Engenheiro de Software (Pleno) · Jun 2023 – Mar 2026
  Quase 3 anos no Projeto Lets, squad de 40+ pessoas; centenas de correções e melhorias de qualidade; migração monólito → microfrontend (Module Federation).
- **Pumpkin Tech** — Desenvolvedor Jr./Pleno · Out 2021 – Jun 2023
  Migração CRA/JS → TypeScript; uploader de KML (1.000+ áreas); servidor próprio de tiles em EC2; app Android/iOS offline-first (WatermelonDB); frontend para plataforma do Governo Federal (SIRENE); sistema imobiliário fullstack (Next.js, PostgreSQL).

## Projetos selecionados

- **Gerenciamento de Clínicas Médicas** (2026, em andamento) — Node.js/NestJS + CQRS + Redis + PostgreSQL, React + TanStack, integração com Cognito, SES, Amplify e Stripe.
- **Lefandom** (e-commerce, 2026) — Node.js/NestJS + React/TanStack, Mercado Pago, migração de Nuvemshop para aplicação própria (99 desempenho / 89 acessibilidade / 100 SEO).
- **Portfólio pessoal** — [brunorobertosantos.com.br](https://brunorobertosantos.com.br/), Astro.
- **Boa Pedida Delivery** (2020) — marketplace multiplataforma (React Native, React, Node.js/Express/Knex), publicado nas duas lojas.
- **Laboratório Dr. Adriano Macedo** (2019) — sistema de resultados de exames (ASP.NET MVC, Entity Framework), em produção por 2-3 anos.

## Skills

**Linguagens:** TypeScript, JavaScript, C#
**Frontend:** React, Next.js, React Native, Vue, TanStack (Query/Router/Table), Tailwind, Vite, SASS
**Backend:** Node.js, Express, NestJS, CQRS, PHP/Laravel (legado)
**Arquitetura:** Microfrontend (Module Federation), migração de sistemas legados, offline-first
**Dados:** PostgreSQL, MySQL/Aurora, Redis, WatermelonDB
**Cloud & DevOps:** AWS (Lambda, EC2/EC2 Spot, RDS/Aurora, Amplify, Cognito, SES), Firebase/Firestore, Docker
**Integrações:** Stripe, Mercado Pago, Google Maps API, IA aplicada (OpenAI, Anthropic/Claude)

## Formação

Bacharelado em Ciência da Computação — Universidade Federal de Alfenas (UNIFAL/MG), 2025.

</div>

<div align="right">

## Estrutura do repositório

```
en/   CV em inglês (.tex + .pdf)
pt/   CV em português (.tex + .pdf)
```

## Como compilar

Requer uma distribuição LaTeX (ex: [TeX Live](https://www.tug.org/texlive/) ou [MiKTeX](https://miktex.org/)).

```bash
cd pt   # ou en
pdflatex CV-Bruno_Roberto_Santos.tex
```

Ou, com `latexmk` (recompila e limpa builds incompletos automaticamente):

```bash
latexmk -pdf CV-Bruno_Roberto_Santos.tex
```

</div>