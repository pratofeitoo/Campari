---
title: "Documento de Requisitos: Plataforma do Censo de Diversidade"
uuid: req-censo-dei-exemplo-2025-09-20-001
type: requisitos-do-projeto
status: aprovado
created_date: 2025-09-20
updated_date: 2025-09-20
author: Líder de Produto, Pilar Insight
tags:
  - requisitos-do-projeto
  - censo-de-diversidade
  - insight
  - lgpd
created: 2025-06-06T22:54
updated: 2025-11-05T09:32
---

# Documento de Requisitos do Projeto (DRP)

## Informações do Projeto

### Nome do Projeto
Programa de Transformação DEI - Plataforma do Censo de Diversidade

### Versão
1.0

### Data de Preparação
2025-09-20

### Preparado por
Líder de Produto, Pilar Insight (DiverCidade Business Hub)

### Status
Aprovado

## Introdução

### Finalidade deste Documento
Este documento define os requisitos funcionais e não funcionais para a plataforma online que será utilizada para conduzir o Censo de Diversidade para o Cliente Exemplo S.A. Serve como a base acordada para o design, desenvolvimento e teste da plataforma, garantindo que o produto final atenda às necessidades de negócio, segurança e privacidade.

### Contexto do Projeto & Necessidade de Negócio
Como parte do Programa de Transformação DEI, a coleta de dados demográficos precisos e seguros é fundamental. A Cliente Exemplo S.A. precisa de uma compreensão clara de sua linha de base demográfica para identificar lacunas de representatividade, medir o progresso ao longo do tempo e informar a criação de estratégias de inclusão eficazes. A plataforma do Censo de Diversidade aborda a necessidade de coletar esses dados de forma anônima, segura e que gere confiança nos colaboradores.

### Escopo
- **Incluído no Escopo dos Requisitos:** A interface do questionário para o colaborador, o mecanismo de autenticação via link seguro, a anonimização e armazenamento seguro dos dados, e o dashboard de resultados agregados para administradores autorizados.
- **Fora do Escopo dos Requisitos:** Análises estatísticas aprofundadas (serviço de consultoria pós-censo), integração direta com o sistema de RH do cliente (a troca de dados será via lista segura), e o plano de comunicação para incentivar a participação (gerenciado pelo pilar Prisma).

### Público-Alvo
Gerentes de Projeto, Desenvolvedores (Insight), Analistas de Dados (Insight), Equipe de Segurança da Informação (Cliente), Diretor de RH (Cliente), Comitê de Diversidade (Cliente).

### Definições, Siglas e Abreviações
- **DEI:** Diversidade, Equidade e Inclusão
- **LGPD:** Lei Geral de Proteção de Dados
- **PII:** Personally Identifiable Information (Informações de Identificação Pessoal)
- **WCAG:** Web Content Accessibility Guidelines

## Metas e Objetivos do Projeto

- **Meta/Objetivo 1:** Coletar dados demográficos de forma segura e anônima para estabelecer uma linha de base quantitativa para o estado da diversidade na Cliente Exemplo S.A.
- **Meta/Objetivo 2:** Fornecer uma ferramenta que garanta a segurança psicológica e a confiança dos colaboradores para maximizar a taxa de adesão e a honestidade das respostas.

## Stakeholders & Usuários

### Principais Stakeholders
- **Diretor de RH (Cliente):** Principal interessado nos resultados para a estratégia de gestão de pessoas.
- **Líder de TI/Segurança (Cliente):** Interessado em garantir a segurança e a conformidade da plataforma.
- **Líder do Pilar Insight (DiverCidade):** Responsável pela entrega e qualidade técnica da plataforma.

### Usuários-Alvo / Personas
- **Tipo de Usuário 1:** Colaborador (Todos os funcionários da Cliente Exemplo S.A.)
  - **Descrição:** Usuário final que preencherá o censo.
  - **Principais Necessidades/Objetivos:** Entender o propósito, sentir-se seguro quanto ao anonimato, preencher o questionário de forma rápida e fácil em qualquer dispositivo.
- **Tipo de Usuário 2:** Administrador de RH (Cliente)
  - **Descrição:** Profissional de RH responsável por acompanhar a iniciativa.
  - **Principais Necessidades/Objetivos:** Monitorar a taxa de adesão em tempo real (sem acesso a respostas individuais) e visualizar os resultados finais em um dashboard agregado.
- **Tipo de Usuário 3:** Analista de Dados (DiverCidade)
  - **Descrição:** Responsável pela análise profunda dos dados.
  - **Principais Necessidades/Objetivos:** Exportar o conjunto de dados brutos 100% anonimizados para análise estatística em ferramentas externas.

## Requisitos Funcionais

| ID Req | Descrição do Requisito                                                                | Prioridade  | Fonte                     |
|--------|--------------------------------------------------------------------------------------|-------------|---------------------------|
| RF-001 | O sistema deve usar links de uso único e seguros para autenticação de cada colaborador. | Obrigatório | Requisito de Segurança    |
| RF-002 | O sistema deve apresentar um questionário online, de múltiplas páginas e responsivo.    | Obrigatório | Colaborador               |
| RF-003 | O sistema deve exibir uma política de privacidade clara e exigir o consentimento do usuário. | Obrigatório | Requisito Legal (LGPD)    |
| RF-004 | O sistema deve permitir que o usuário salve o progresso e continue depois.             | Desejável   | Colaborador               |
| RF-005 | O sistema deve fornecer um dashboard em tempo real mostrando apenas a taxa de adesão geral. | Obrigatório | Administrador de RH       |
| RF-006 | O sistema deve fornecer um dashboard pós-censo com visualizações de dados agregados.    | Obrigatório | Administrador de RH       |
| RF-007 | O acesso ao dashboard de resultados deve ser restrito por função (role-based).         | Obrigatório | Requisito de Segurança    |
| RF-008 | O sistema deve permitir a exportação segura do dataset anonimizado em formato CSV.      | Obrigatório | Analista de Dados         |
| RF-009 | O sistema deve suprimir automaticamente a exibição de dados para grupos com menos de 5 pessoas. | Obrigatório | Requisito de Privacidade  |

## Requisitos Não Funcionais (RNFs) / Qualidade

### Desempenho
- **RNF-DESEMP-01:** O tempo de carregamento de cada página do questionário deve ser inferior a 2 segundos.
- **RNF-DESEMP-02:** O sistema deve suportar 1.000 usuários simultâneos durante picos de acesso.

### Segurança
- **RNF-SEG-01:** Todos os dados em trânsito devem ser criptografados com HTTPS/TLS 1.2+.
- **RNF-SEG-02:** Todos os dados em repouso (banco de dados) devem ser criptografados (padrão AES-256).
- **RNF-SEG-03:** A plataforma deve passar por uma análise de vulnerabilidades para mitigar os riscos do OWASP Top 10.

### Usabilidade / Experiência do Usuário (UX)
- **RNF-USAB-01:** A interface deve ser compatível com as versões mais recentes do Chrome, Firefox e Safari.
- **RNF-USAB-02:** A interface deve ser totalmente responsiva para uso em desktops e dispositivos móveis.
- **RNF-USAB-03:** A plataforma deve atender aos critérios de acessibilidade do WCAG 2.1 Nível AA.

### Confiabilidade / Disponibilidade
- **RNF-CONF-01:** O sistema deve ter um uptime de 99.9% durante o período de 4 semanas de coleta de dados.

### Legal / Conformidade
- **RNF-LEGAL-01:** A plataforma e o processo de tratamento de dados devem estar em total conformidade com a Lei Geral de Proteção de Dados (LGPD) do Brasil.

## Requisitos de Dados

- **DADO-01:** O esquema de dados deve incluir, mas não se limitar a: Identidade de Gênero, Orientação Sexual, Raça/Cor (padrão IBGE), Pessoa com Deficiência (PCD), Faixa Etária, Localidade, Nível de Senioridade e Departamento.
- **DADO-02:** Para garantir a segurança psicológica, todos os campos de resposta do questionário, exceto o termo de consentimento, devem ser de preenchimento opcional.
- **DADO-03:** O banco de dados de respostas deve ser estruturalmente separado de qualquer informação de identificação pessoal (PII) usada para a distribuição dos links.
- **DADO-04:** Backups diários e criptografados do banco de dados de respostas devem ser realizados.

## Requisitos de Interface

### Interface do Usuário (UI)
- **UI-01:** O design da interface deve ser limpo, intuitivo e neutro.
- **UI-02:** A interface deve incorporar o logo e as cores primárias da Cliente Exemplo S.A., conforme seu guia de marca.

### Interfaces de Software / APIs
- **API-01:** Nenhuma API externa será exposta. Todas as APIs internas entre o frontend e o backend devem ser autenticadas e seguras.

## Premissas e Dependências

### Premissas
- **PREM-01:** O cliente fornecerá uma lista completa e precisa de e-mails de todos os colaboradores para a distribuição dos links únicos.
- **PREM-02:** Os colaboradores possuem acesso à internet e a um navegador web moderno para responder ao censo.

### Dependências
- **DEP-01:** Dependente da equipe de TI do cliente para garantir que os e-mails enviados pela plataforma não sejam bloqueados por filtros de spam.
- **DEP-02:** Dependente da aprovação do departamento jurídico do cliente sobre o texto da Política de Privacidade e do Termo de Consentimento.

## Aprovações

- **Patrocinador de Negócio / Product Owner:**
  - **Nome:** [Nome do Diretor de RH, Cliente Exemplo S.A.]
  - **Cargo:** Diretor(a) de Recursos Humanos
  - **Data de Aprovação:** 2025-09-20

- **Líder Técnico / Arquiteto:**
  - **Nome:** [Nome do Líder, Pilar Insight]
  - **Cargo:** Líder de Produto e Dados
  - **Data de Aprovação:** 2025-09-20

- **Gerente de Projeto:**
  - **Nome:** PF Rezende
  - **Cargo:** Gerente de Projeto
  - **Data de Aprovação:** 2025-09-20

---
FIM DO DOCUMENTO
---