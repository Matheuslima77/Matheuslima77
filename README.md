# Matheus Lima
**Founder @ TheBaseCompany | Backend & AI Engineer**

> Construindo infraestruturas escaláveis, integrações de alta performance e agentes autônomos para automação de negócios e fluxos de atendimento *high-ticket*. 

Acredito que a verdadeira engenharia de software opera nos bastidores: transações atômicas, segurança de borda (Edge) e orquestração assíncrona impecável. Meu foco atual é o desenvolvimento de arquiteturas SaaS orientadas a eventos e sistemas **RAG (Retrieval-Augmented Generation)** aplicados ao mercado imobiliário e comercial.

---

### ⚙️ Tech Stack & Infraestrutura

Minhas decisões de stack são baseadas em performance, resiliência e controle de estado:

* **Arquitetura & Backend:**
    ![TypeScript](https://img.shields.io/badge/TypeScript-121212?style=for-the-badge&logo=typescript&logoColor=white)
    ![Node.js](https://img.shields.io/badge/Node.js-121212?style=for-the-badge&logo=node.js&logoColor=white)
    ![Next.js](https://img.shields.io/badge/Next.js_14+-121212?style=for-the-badge&logo=next.js&logoColor=white)
* **Dados & Estado:**
    ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-121212?style=for-the-badge&logo=postgresql&logoColor=white)
    ![Supabase](https://img.shields.io/badge/Supabase-121212?style=for-the-badge&logo=supabase&logoColor=white)
    ![Vector Databases](https://img.shields.io/badge/Vector_DBs_(RAG)-121212?style=for-the-badge&logo=databricks&logoColor=white)
* **Automação & IA:**
  
    ![n8n](https://img.shields.io/badge/n8n_Workflows-121212?style=for-the-badge&logo=n8n&logoColor=white)
    ![OpenAI](https://img.shields.io/badge/OpenAI_LLMs-121212?style=for-the-badge&logo=openai&logoColor=white)
    ![Claude](https://img.shields.io/badge/Claude_AI-121212?style=for-the-badge&logo=anthropic&logoColor=white)
* **DevOps & Deploy:**
    ![Docker](https://img.shields.io/badge/Docker-121212?style=for-the-badge&logo=docker&logoColor=white)
    ![Google Antigravity](https://img.shields.io/badge/Google_Antigravity-121212?style=for-the-badge&logo=googlecloud&logoColor=white)
    ![VPS](https://img.shields.io/badge/VPS_Hosting-121212?style=for-the-badge&logo=linux&logoColor=white)

---

### 🏗️ Arquitetura em Destaque

#### [Omnichannel Real Estate CRM & AI Orchestration](https://github.com/Matheuslima77/thebasecompany-architecture-showcase)
**Link aperentação:** https://www.youtube.com/watch?v=sgbTkTDxTHw
*Sistema proprietário (Closed-Source) projetado para o mercado imobiliário.*

O sistema integra automação de vendas e atendimento autônomo via WhatsApp/Instagram, qualificando leads e alimentando diretamente um pipeline Kanban de gestão.

**Desafios Arquiteturais Resolvidos:**
1.  **Multi-Tenant Atômico:** Substituição de *Triggers* frágeis de banco de dados por **PostgreSQL RPCs**. Implementação de lógica `UPSERT` estrita para garantir transações atômicas, eliminando condições de corrida durante o provisionamento simultâneo de contas e workspaces.
2.  **Segurança em Camada Edge:** Blindagem de rotas de ponta a ponta utilizando **Next.js Edge Runtime Middleware**. A validação de sessão (RBAC) e injeção de cabeçalhos de segurança ocorrem antes mesmo da requisição atingir o servidor Node.js.
3.  **Orquestração Híbrida de IA:** Integração robusta entre fluxos **n8n e a API da OpenAI** (Agente Laís) para gerenciar o estado da conversa e a intenção do usuário, garantindo um *handoff* perfeito entre a IA de qualificação e a interface do corretor.

> **Explore o Showcase:** Para visualizar trechos de código reais (`Server Actions`, `Edge Middleware`, e scripts `SQL`) que sustentam essa infraestrutura, visite o [TheBaseCompany Architecture Showcase](https://github.com/Matheuslima77/thebasecompany-architecture-showcase).

---

### 📬 Contato & Links
* **LinkedIn:** [https://www.linkedin.com/in/matheus-lima-190931186/](#)
* **Localização:** Rio de Janeiro, Brasil
