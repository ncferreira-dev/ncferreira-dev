# Olá, eu sou o Nícolas 👋

Desenvolvedor full-stack. Construo sistemas de verdade, em produção, não protótipo nem landing solta: CRM com controle de acesso e auditoria, agente de IA que atende cliente sozinho pelo WhatsApp, e-commerce do zero.

Minha régua é simples: **o que eu entrego roda, tem teste, e sobrevive ao usuário real digitando errado.**

---

## O que eu construo

**Back-end**
NestJS · Prisma · PostgreSQL · arquitetura multi-tenant · autenticação JWT e OAuth · controle de acesso por permissão e hierarquia · trilha de auditoria · integração com Stripe

**Front-end**
Next.js · React · TypeScript · Tailwind CSS · GSAP · Framer Motion

**Agentes de IA**
Integração com a API da Anthropic (Claude) em loop de tool-use: o modelo consulta dados reais e age dentro de regras de negócio, nunca inventa. Já construí um agente que atende cliente final **dentro do WhatsApp**, por texto ou por áudio. A pessoa conversa normal, sem app, sem formulário, sem precisar do computador; o agente entende, consulta o que existe de verdade e resolve ali mesmo.

**O que não aparece na tela**
Testes automatizados, CI que barra código quebrado antes do ar, banco protegido contra corrida no nível de constraint, dado sensível nunca gravado em texto puro.

---

## Projetos em destaque

### 🩺 [CRM de compliance](https://github.com/ncferreira-dev/crmdoctor-quality)
Sistema interno completo para uma consultoria de compliance farmacêutico: gestão de clientes, projetos regulatórios, prazos, chamados. Controle de acesso por cargo e nível verificado em toda rota, trilha de auditoria com autor, alertas automáticos de prazo com e-mail diário, job agendado com monitor de saúde.

`TypeScript` `NestJS` `Prisma` `PostgreSQL` `Next.js` `Tailwind CSS` `JWT` `Argon2` `Resend` `Docker` `EasyPanel` `Vercel` `Jest`

### 📅 [Agendamento conversacional com IA](https://github.com/ncferreira-dev/agenda-ai)
SaaS multi-tenant onde o cliente final marca horário **conversando no WhatsApp**, por mensagem ou áudio, sem formulário. Um agente em loop de tool-use consulta a agenda real e marca, nunca inventa horário. O motor de disponibilidade é puro e testado, e o banco tem uma exclusion constraint que torna overbooking impossível mesmo sob concorrência. Cobrança recorrente, autenticação do dono via login e Google, lembrete automático com confirmação de volta no próprio WhatsApp.

`TypeScript` `NestJS` `Prisma` `PostgreSQL` `Next.js` `Anthropic API` `WhatsApp Cloud API` `Stripe` `Google OAuth` `JWT` `Argon2` `Docker` `GitHub Actions` `Vitest`

### 🥾 [Caqui Trekking](https://github.com/ncferreira-dev/caqui-trekking)
Site de ecoturismo com loja, catálogo e CRM interno da Caqui Trekking, para gerenciar viagens, guias e saídas. Tudo numa aplicação Next.js só, sem back-end separado. No ar em produção.

`TypeScript` `Next.js` `Prisma` `PostgreSQL` `Cloudinary` `Vercel` `Vitest`

### 💍 [Dália Semijoias](https://github.com/ncferreira-dev/dalia-semijoias)
E-commerce completo em MERN stack para venda de semijoias. Peguei o projeto ainda no esboço inicial e conduzi sozinho o resto: front-end, back-end, construção das APIs, design system, CRM interno e hospedagem em produção.

`MongoDB` `Express` `React` `Node.js`

### 🧵 [Mestre do Terno](https://github.com/ncferreira-dev/mestre-dos-ternos)
Catálogo digital para a bio do Instagram: uma landing page que direciona pra página de vendas, com botões conectando direto aos canais de venda (Mercado Livre, Shopee e outros) e scroll suave sincronizado ao motor de animação.

`React` `Vite` `Tailwind CSS` `React Router` `GSAP` `Lenis`

---

## Como entrar em contato

Aberto a oportunidades e projetos novos. Fica à vontade para abrir uma conversa em qualquer um dos repositórios acima.
