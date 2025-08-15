📚 StudMed

StudMed é um chatbot de Inteligência Artificial focado em auxiliar estudantes de medicina, oferecendo respostas baseadas em literatura médica confiável e permitindo o gerenciamento de materiais de estudo.

🚀 Tecnologias Utilizadas
- Next.js — Frontend e Backend
- TypeScript — Tipagem estática
- TailwindCSS + ShadcnUI — Estilização e componentes
- PostgreSQL (Supabase) — Banco de dados
- Prisma ORM — Comunicação com o banco
- NextAuth — Autenticação
- OpenAI API — Processamento de linguagem natural
- Adversel SDK — Integrações e deploy

🎯 Objetivos Principais
1. Criar um chatbot com respostas precisas baseadas em fontes médicas.
2. Implementar funcionalidades de busca, histórico e personalização do estudo.
3. Garantir usabilidade, performance e escalabilidade do sistema.

📅 Planejamento de Sprints

Sprint 1 — Configuração da base e arquitetura
- Configuração do projeto (Next.js, TypeScript, ESLint, Prettier, Husky, CI/CD).
- Setup do banco de dados (Supabase + Prisma).
- Autenticação com NextAuth.
- Deploy inicial na Vercel.

Sprint 2 — Chat básico e RAG inicial
- Interface de chat (Tailwind + ShadcnUI).
- API `/api/chat` conectada à LLM.
- Upload e indexação de PDFs no banco.
- Histórico de mensagens por usuário.

Sprint 3 — Funcionalidades avançadas e personalização
- Sistema de tópicos de estudo e filtros no RAG.
- Feedback de respostas (👍/👎).
- Painel para gerenciamento de materiais.
- Métricas de uso por usuário.

Sprint 4 — Otimização, testes e refinamento do MVP
- Otimização de consultas e tempo de resposta.
- Testes automatizados.
- Melhorias de UI/UX.
- Documentação e onboarding.

📂 Estrutura do Projeto (simplificada)
/app
  /api
    /chat
  /auth
/components
/lib
/prisma
  schema.prisma

📦 Como Rodar Localmente
1. Clonar o repositório
   git clone https://github.com/seu-usuario/studmed.git
2. Entrar na pasta
   cd studmed
3. Instalar dependências
   npm install
4. Configurar variáveis de ambiente
   cp .env.example .env.local
5. Rodar o projeto
   npm run dev

📄 Licença
Este projeto está sob a licença MIT — sinta-se livre para usar e contribuir.
