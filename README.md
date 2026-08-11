# Leandro Oliveira de Sousa

Desenvolvedor fullstack focado em produtos AI-first: backends em NestJS, apps em Flutter e agentes de IA (Claude/OpenAI) integrados ao core do negócio — não como "chatbot anexo", mas como camada que reaproveita os mesmos services que a API e o app usam.

---

## 🚀 Projetos em destaque

### [Sábio.dev](https://github.com/Sabe-o-dev)

Sistema de gerenciamento de projetos estilo Jira/Trello com um assistente de IA (**Sábis**) integrado ao Slack.

- Gestão ágil completa: projetos, sprints (1 ativa por projeto), tarefas com código automático (SAB-123), subtarefas, comentários — com soft delete e RBAC (Admin/Dev/Viewer).
- Sábis: agente Claude via Slack com tool use sobre os services de domínio — consulta projetos/sprints, cria tarefas, gera relatórios de sprint e ranking de equipe, e transforma uma proposta em PDF em projeto estruturado completo (projeto + sprint + tarefas, atomicamente).
- Daily Bot baseado em regras (sem IA generativa): dispara perguntas diárias no Slack, reconhece códigos de tarefa nas respostas e publica resumo consolidado.
- Planning Poker em tempo real (WebSocket + Redis), time tracking, geração de propostas comerciais em PDF, webhooks do GitHub associando commits/PRs à atividade de cada membro, bot de WhatsApp (Evolution API + OpenAI) e site institucional com blog gerado por IA.
- Stack: NestJS 11 · MongoDB Atlas · Firebase Admin · Redis/Socket.IO · Anthropic Claude · Flutter · Next.js 15 · Cloud Run

### [Apex](https://github.com/Sabe-o-dev)

Plataforma de gamificação de performance para times de engenharia.

- Pontuação automática via GitHub webhooks (PRs, reviews, issues) e pontuação manual com auditoria por IA (evidências em foto, link ou áudio).
- Leaderboard em tempo real, loja de recompensas, missões/challenges, streaks e notificações via Slack/FCM.
- API com 24 módulos de domínio (achievements, ranking, multipliers, streak, intel, member-status, entre outros).
- Stack: NestJS · MongoDB · Flutter (mobile/web/admin) · Next.js (landing) · Firebase

### [VitaAI](https://github.com/Sabe-o-dev)

App de criação de currículos com IA.

- Geração de currículo assistida por IA (OpenAI), com exportação em PDF (server-side rendering via Puppeteer/React-PDF).
- Autenticação Firebase (Google + e-mail/senha), upload de foto de perfil.
- Stack: NestJS · MongoDB Atlas · Firebase Auth/Storage · OpenAI · Flutter (GetX)

---

## 🛠️ Stack

Backend: NestJS · TypeScript · MongoDB (Mongoose) · Redis · Socket.IO

Mobile/Web: Flutter/Dart (BLoC, GetX) · Next.js · React

IA: Anthropic Claude (tool use / agentes) · OpenAI

Infra: Firebase (Auth, Storage, Hosting) · Google Cloud Run · GitHub Actions/Webhooks

Padrões: arquitetura modular por domínio, soft delete, RBAC, integração com Slack/WhatsApp

---

## 📫 Contato

- GitHub: [@leandrooliver-dev](https://github.com/leandrooliver-dev)
