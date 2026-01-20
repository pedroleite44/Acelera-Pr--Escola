# Acelera-Pré--Escola
🚀 Acelera Pré-Escola: SaaS Full Stack para Automação da Comunicação Escolar
Transformando a burocracia diária em 3 cliques. Um projeto Full Stack com foco em IA e Automação.

O Acelera Pré-Escola é um Sistema de Gestão Escolar (SaaS) que resolve o principal ponto de dor em creches e pré-escolas: a comunicação diária entre professores e pais. Adaptado de um modelo de sucesso em clínicas de estética, o projeto demonstra a capacidade de Análise de Requisitos, Modelagem de Domínio e Desenvolvimento Full Stack com foco em eficiência e escalabilidade.



🎯 O Problema e a Solução (Business Value)
Aspecto	O Problema	A Solução Acelera
Tempo do Professor	Gasto excessivo com anotações manuais e relatórios.	Diário de Bordo de 3 Cliques: Interface otimizada para registro rápido de rotinas (Alimentação, Sono, Higiene, Atividade).
Comunicação com Pais	Informações desencontradas, atrasos e uso de aplicativos genéricos (WhatsApp).	Resumo Diário Mobile-First: Notificações em tempo real e visualização clara da rotina da criança, focando na experiência do usuário.
Gestão	Falta de dados estruturados para análise pedagógica e administrativa.	Dados Estruturados: Coleta de dados padronizada para futura integração com LLMs (Large Language Models) para relatórios automáticos e análise de sentimento.


💻 Stack Tecnológico (Full Stack)
Este projeto é uma demonstração de proficiência em tecnologias modernas e escaláveis:

Camada	Tecnologia	Propósito
Frontend	Next.js 14 (App Router), TypeScript, Tailwind CSS, Shadcn/UI	Performance, SEO e UI/UX profissional e consistente.
Backend/API	tRPC, TypeScript	API type-safe, garantindo segurança e integridade entre frontend e backend.
Banco de Dados	PostgreSQL, Prisma 7	ORM moderno e banco de dados relacional robusto para integridade de dados.
Autenticação/Pagamento	NextAuth (Planejado), Stripe (Planejado)	Sistema de autenticação baseado em roles (Admin, Teacher, Parent) e gestão de assinaturas.


🤖 Foco em Automação e IA (Analista de Prompts)
A arquitetura do Acelera foi intencionalmente desenhada para a futura integração de Inteligência Artificial, um ponto crucial para a vaga de Analista de Prompts e Automação:

1	Estrutura de Dados para LLMs: O prisma/schema.prisma define 8 tabelas com relações claras, garantindo que os dados de rotina (DailyLog) sejam facilmente consumíveis por modelos de IA para gerar relatórios pedagógicos personalizados.
2	Automação de Processos: O sistema em si é uma automação do processo de comunicação. O "Diário de Bordo de 3 Cliques" é o ápice da otimização de fluxo de trabalho.
3	Preparação para Análise de Sentimento: A estrutura de notificações e comentários está pronta para ser alimentada em um LLM para monitorar o humor geral dos pais e professores, permitindo intervenções proativas da coordenação.



🏗️ Arquitetura e Modelagem de Dados
O sistema utiliza uma arquitetura baseada em Roles (Admin, Teacher, Parent) com controle de acesso granular via middleware do tRPC.

📄 prisma/schema.prisma (Visão Geral)
O banco de dados é o coração do sistema, modelado para garantir a integridade e a escalabilidade:

•	Tabelas Chave: School, User, Class, Student, StudentParent, DailyLog, Media, Notification.
•	Relacionamentos: Relações One-to-Many e Many-to-Many bem definidas para gerenciar a complexidade de múltiplas escolas, turmas e alunos.
•	Enums: Uso de UserRole para tipagem estrita dos níveis de acesso.



🛣️ Próximos Passos (MVP)
4	Refatoração Frontend: Conclusão da migração de todas as 4 telas principais restantes para Shadcn/UI para um design profissional e coeso.
5	Validação de Mercado: Execução de entrevistas com coordenadores para validar o Product-Market Fit e o modelo de precificação (R$197/mês fixo).
6	Integração Stripe: Implementação do sistema de pagamento por assinatura.



👨‍💻 Desenvolvedor
Pedro Henrique Dos Santos Leite
•	LinkedIn
•	GitHub
•	Foco: Full Stack Development, Análise de Sistemas, Automação e Integração de IA.
