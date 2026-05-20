<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6&height=120&section=header" />

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=30&pause=1000&color=A7A5F7&background=2BFFF600&center=true&vCenter=true&width=600&height=50&lines=Arthur+Gabriel;Software+Engineer;Backend+%26+Mobile+Engineer;Fullstack+Developer" alt="Typing SVG" />
  </a>
</p>

## 🚀 Sobre Mim

Gosto de entrar em problemas difíceis cedo — quando o domínio ainda está sendo descoberto e as decisões de arquitetura importam de verdade. Construo produtos do zero até a escala, com foco em sistemas que sobrevivem ao próprio crescimento.

Atualmente mantendo aplicações em produção com **50k+ usuários ativos** e desenvolvendo um SaaS multi-tenant do início ao fim — do banco de dados ao deploy.

| Resultado | Contexto |
|-----------|----------|
| **50k+ usuários ativos** | App fiscal com 99.2% crash-free rate em produção |
| **Latência 3-5s → <100ms** | Cache estratégico + refatoração de queries Oracle SQL |
| **0% → 75% cobertura de testes** | Mudança de cultura em 6 meses via TDD |
| **Idempotência em pagamentos** | Retry logic e transações atômicas em fluxos financeiros críticos |
| **RAG + agentes LLM** | Pipelines de extração estruturada e recuperação semântica em produção |

---

## 💼 Projetos em Destaque

### 🤖 [Colab.IA — Plataforma de Compliance Trabalhista com IA](https://colab.ia.br/)

Sistema de auditoria de folhas de ponto para empresas, com validação automática contra CLT e Convenções Coletivas, ranking de risco por colaborador e assistente via LLM.

**Stack:** Java 25 · Spring Boot · PostgreSQL · RabbitMQ · LangChain4j · Angular · Google Cloud Storage
- Arquitetura multi-tenant com isolamento por empresa, suportando múltiplas filiais com regras de compliance independentes.
- Auditoria de 100% das folhas de ponto (não amostragem) com detecção automática de inconformidades.
- Integração com múltiplos LLMs via LangChain4j para extração e análise de dados.
- Notificações em tempo real via WebSocket com broadcast cross-instance por RabbitMQ.

---

### 🪶 [Sankofa — Marketplace de Afroempreendedores](https://www.sankofanegociosnegros.com/)

Plataforma que conecta consumidores a negócios afrobrasileiros, dando visibilidade e infraestrutura digital a empreendedores que historicamente não tiveram acesso a esses recursos.

**Stack:** NestJS · PostgreSQL · Prisma · Redis · Cloudflare R2 · Docker
- Auth com JWT + Refresh Token, tokens armazenados como hash e bloqueio por tentativas falhas.
- Sistema de membership com ciclo de vida completo: planos, proração de upgrade e expiração automática via job noturno.
- Auditoria imutável de todas as ações administrativas com dados anteriores, novos e IP do responsável.
- Upload e processamento de imagens com otimização automática antes de armazenar no Cloudflare R2.
- Em desenvolvimento ativo — produto com propósito real, construído do zero.

---

### 🏢 [ConsultaAI — SaaS de Consultas de Dados Públicos](https://consultaai.net.br/)

Plataforma multi-tenant para consulta de CPF, CNPJ com modelo de créditos pré-pagos, múltiplos providers com fallback automático e processamento de pagamentos via PIX.

**Stack:** Next.js · NestJS · PostgreSQL · Prisma · Redis · Cloudflare R2 · Docker
- Isolamento multi-tenant com carteira de créditos por usuário e histórico de movimentações.
- Sistema de providers com fallback automático e monitoramento de saúde entre APIs externas.
- Integração com gateway Asaas via webhooks para processamento assíncrono de pagamentos.
- Backup automatizado do banco de dados com retenção no Cloudflare R2.
- Deploy em VPS Hostinger gerenciado via Dokploy com monitoramento de erros pelo Sentry.

---

### 📱 App Fiscal — Gestão de Créditos Tributários
Aplicativo mobile para consulta de créditos fiscais integrado com APIs governamentais.

**Stack:** Flutter · Spring Boot · Oracle SQL · Firebase  
- 50k+ usuários ativos com 99.2% crash-free rate em produção.
- Arquitetura MVVM com persistência local via Hive focado na experiência de usuário.
- Integração com OAuth 2.0 (gov.br) e otimização de latência de 3-5s para <100ms.
- Push notifications via Firebase Cloud Messaging e deep linking para navegação direta.
- Monitoramento de erros e estabilidade em tempo real com Firebase Crashlytics.

---

## 🛠️ Stack Técnica

### **Mobile & Frontend**
<p align="left">
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" />
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white" />
</p>

### **Backend & Cloud**
<p align="left">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white" />
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white" />
  <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" />
</p>

### **Databases & DevTools**
<p align="left">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white" />
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Sentry-362D59?style=for-the-badge&logo=sentry&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" />
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white" />
</p>

---

### **Arquitetura & Qualidade**
- 🏛️ **Patterns:** Clean Architecture, MVVM, Hexagonal Architecture, SOLID e Design Patterns.
- 🧪 **Testing:** Unit Testing, Integration Testing, E2E e TDD (foco em cobertura resiliente).
- ⚙️ **DevOps:** CI/CD Pipelines, Docker, Dokploy e automação com Bash.
- 💳 **Integrations:** Gateways de pagamento, OAuth 2.0 (Gov.br), LLMs via LangChain4j e APIs RESTful.
- 📈 **Observabilidade:** Monitoramento de erros e performance com Sentry e Firebase Crashlytics.

---

## 📈 Estatísticas
<p align="center">
  <img height="180" src="https://github-stats-extended.vercel.app/api?username=ArthurGabrieel&show_icons=true&theme=dark&include_all_commits=true&count_private=true" />
  <img height="180" src="https://github-stats-extended.vercel.app/api/top-langs/?username=ArthurGabrieel&layout=compact&langs_count=7&theme=dark" />
</p>

---

## 📫 Vamos nos conectar?
<p align="center">
  <a href="mailto:arthurelgg@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/arthurgabrieel/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
</p>

<p align="center">
  <i>Aberto a discussões sobre Engenharia de Software e oportunidades Pleno/Sênior.</i>
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6&height=120&section=footer" />
