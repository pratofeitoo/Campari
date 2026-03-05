---
title: Índice - TEMPLATE_DIRETÓRIO
description: Sistema completo de templates e framework para gestão de conhecimento baseado em IDEKnow v2.0
created: 2025-11-05
last_updated: 2025-12-02
type: index
---

# 📚 Template Directory – Sistema de Gestão de Conhecimento

**Sistema abrangente de templates baseado no Framework IDEKnow v2.0 para organização de clientes, projetos, reuniões, documentos e operações.**

📅 **Última Atualização:** 2 de Dezembro de 2025 | 📊 **6 Diretórios Principais** | 📄 **65 Arquivos Totais** | 📝 **65 Arquivos Markdown**

---

## 🎯 Visão Geral e Propósito do Framework

Este Template Directory funciona como um **repositório de padrões e templates reutilizáveis** baseado no **IDEKnow v2.0**, um framework de gestão de conhecimento aumentado por IA. A estrutura é otimizada para:

- **Gestão de Clientes**: Perfis, contatos e documentação de relacionamento com clientes
- **Gestão de Projetos**: Briefings, planejamento estratégico, pesquisa de mercado e deliverables
- **Gestão de Reuniões**: Documentação padronizada de reuniões e anotações
- **Operações e Conformidade**: Documentos legais, contratos e procedimentos
- **Biblioteca de Templates**: Conjunto completo de templates reutilizáveis para workflows recorrentes
- **Framework e Padrões**: Regras, esquemas e diretrizes para garantir consistência em toda a organização

---

## ⚡ Navegação Rápida

| 📌 Seção | 🎯 Propósito | ⏱️ Quando Usar |
|----------|-----------|----------|
| **🎨 00_meta** | Regras, padrões e schemas do framework | Configurar novos documentos, garantir conformidade |
| **👥 01_client** | Perfis de clientes e contatos | Gerenciar relacionamentos, referências de cliente |
| **🚀 02_projects** | Planejamento e documentação de projetos | Iniciar projetos, briefings, pesquisa de mercado |
| **📅 03_meetings** | Anotações de reuniões | Documentar reuniões, rastrear decisões |
| **📁 04_documents** | Repositório de documentos finais | Armazenar relatórios, documentos legais |
| **🎨 05_templates** | Biblioteca completa de templates reutilizáveis | Replicar workflows, padronizar saídas |

---

## 📂 Guia Detalhado de Diretórios

### 📋 **00_meta** – Regras, Padrões e Configuração do Framework

**O núcleo normativo do sistema – Define como toda a documentação deve ser estruturada e mantida**

- **Arquivos**: 24
- **Propósito**: Centralizar todas as regras, esquemas, padrões e diretrizes para padronização de conteúdo
- **Componentes Principais**:
  - **FR00_Filosofia Central.md** – Visão geral do IDEKnow v2.0: transformar IDEs em hubs de gestão de conhecimento aumentado por IA
  - **FR01_estrutura_de_pastas.md** – Padrões de organização hierárquica
  - **FR02_convencoes_nomeacao_arquivos.md** – Convenções de nomenclatura consistentes
  - **FR03_esquema_base_yaml_frontmatter.md** – Schema obrigatório de metadados YAML (base para todos os docs)
  
- **Schemas Especializados** (FR03a–FR03i):
  - Perfil de Cliente | Atas de Reunião | Contratos | Perfis de Contato | Tarefas | Eventos | Artigos de Conhecimento | Observações
  
- **Diretrizes de Qualidade**:
  - FR04 – Padrões de qualidade Markdown
  - FR05 – Estratégia de links e relacionamentos
  - FR06 – Tagging e categorização
  - FR07a/b – Workflows (reuniões e observações)
  - FR08 – Dicas de interação com IA

- **Grafo de Conhecimento**:
  - `Diretrizes para Criação de Entidades e Relacionamentos.md` – Como criar conexões semânticas
  - `Tipos Padrão de Entidades e Esquemas.md` – Entidades padronizadas
  - `Relações Padrão do Grafo de Conhecimento.md` – Relacionamentos permitidos

- **Configuração Técnica**:
  - `.github/copilot-instructions.md` – Instruções para GitHub Copilot e IA
  - `.vscode/settings.json` – Configurações otimizadas do VS Code

**📌 Caso de Uso**: Consulte aqui ao criar novos documentos. Estes arquivos definem os "padrões de ouro" que todos os outros documentos devem seguir.

---

---

### 👥 **01_client** – Gestão de Clientes e Contatos

**Hub centralizado para perfis de clientes, dados de contato e documentação de relacionamento**

- **Arquivos**: 1
- **Propósito**: Armazenar informações padronizadas de clientes e pontos de contato para referência rápida
- **Arquivos Principais**:
   - `perfil_contato.md` – Template de contato individual com dados e relacionamentos
   
- **Integração**: Documentos neste diretório devem seguir o schema FR03d (Perfil de Contato)

**📌 Caso de Uso**: Manter registro centralizado de clientes ativos, preencher informações de contato, vincular a projectos e reuniões.

---

---

### 🚀 **02_projects** – Planejamento e Documentação de Projetos

**Área de trabalho para gerenciar projetos ativos com briefings, planejamento estratégico e pesquisa**

- **Subdiretórios**: 5 (Briefing_projeto, Planejamento_campanha, Planejamento_projeto, pesquisa_de_mercado, questionário_marcas)
- **Arquivos**: 9
- **Propósito**: Centralizar documentação de projetos com templates prontos para uso

**Estrutura de Subdiretórios**:

#### **Briefing_projeto/**
- `project_brief_template.md` – Template inicial para briefing de novos projetos com escopo, objetivos e entregáveis

#### **Planejamento_campanha/** (3 arquivos)
- `Documento de Planejamento de Campanha.md` – Plano estratégico completo para campanhas de marketing
- `ESG Campaign Objectives & Key Performance Indicators (KPIs).md` – Definição de metas e métricas
- `Framework de Mensagens da Campanha.md` – Estrutura de narrativa e mensagens-chave

#### **Planejamento_projeto/** (5 arquivos)
- `MODELO_DOCUMENTO_PLANEJAMENTO_PROJETO.md` – Template abrangente para planejamento de projetos complexos
- `MODELO_DOCUMENTO_REQUISITOS_PROJETO.md` – Detalhar requisitos de projeto
- `protocolo_tomada_decisao_projeto.md` – Protocolo padronizado para decisões
- `template_plano_comunicacao_projeto.md` – Plano de comunicação do projeto

#### **pesquisa_de_mercado/**
- `pesquisa_de_mercado.md` – Template de pesquisa seguindo metodologia de Kotler

#### **questionário_marcas/**
- `Brand Profile Questionnaire.md` – Questionário estruturado para definir perfil de marca

**📌 Caso de Uso**: Iniciar novo projeto → Escolha o template apropriado → Adapte para seu contexto específico → Vincule a clientes e equipes.

---

---

### 📅 **03_meetings** – Anotações de Reuniões

**Repositório de transcrições e anotações de reuniões**

- **Subdiretórios**: 1 (transcripts)
- **Arquivos**: 0 templates
- **Propósito**: Armazenar anotações e registros de reuniões realizadas
   
- **Integração**: Use templates de ata de reunião de `05_templates/` (ex: `atas_reuniao_template.md`)

**📌 Caso de Uso**: Armazenar registros de reuniões com clientes, equipes internas ou stakeholders.

---

---

### 📁 **04_documents** – Repositório de Documentos Finais

**Armazenamento organizado de documentos gerados, relatórios e arquivos de conformidade**

- **Subdiretórios**: 2 (legal, reports)
- **Arquivos**: 4
- **Propósito**: Centralizar documentos finalizados, relatórios executivos e documentação legal

**Estrutura de Subdiretórios**:

#### **legal/** – Documentos Legais e de Conformidade
- `.keep` – Marcador de diretório (aguardando documentos legais)
- **Propósito**: Armazenar contratos, acordos e documentação legal

#### **reports/** – Relatórios e Resultados

**reports/ESG_campaign_performance/**
- `ESG Campaign Performance Report.md` – Template de relatório de desempenho de campanha com métricas e análise

**reports/Status_report/** (3 arquivos)
- `status_report_template.md` – Template de relatório de status periódico de projetos
- `REPORT_5_Quarterly_Performance.md` – Relatório trimestral de desempenho
- `Template de Registro de Ações e Problemas.md` – Registro de ações e issues
- `Documento de revisão projetos finalizados.md` – Revisão de projetos concluídos

**📌 Caso de Uso**: Armazenar documentos finalizados, relatórios gerenciais e documentação de conformidade. Referenciar como saída do projeto.

---

---

### 🎨 **05_templates** – Biblioteca Completa de Templates Reutilizáveis

**A maior seção – 26 templates prontos para uso, organizados em templates principais e complementares**

- **Subdiretórios**: 2 (Docs_complementares)
- **Arquivos**: 26 templates
- **Propósito**: Fornecer biblioteca reutilizável para workflows recorrentes

**Estrutura de Templates**:

#### **Docs_complementares/** (26 templates de suporte)
Biblioteca completa de templates para workflows diversos:

| Template | Uso |
|----------|-----|
| Brand Profile Questionnaire.md | Definir perfil de marca e posicionamento |
| Documento de Planejamento de Campanha.md | Planejar campanhas de marketing |
| ESG Campaign Objectives & KPIs.md | Definir objetivos e métricas de sucesso |
| ESG Campaign Performance Report.md | Relatar resultados de campanhas |
| Framework de Mensagens da Campanha.md | Estruturar narrativas e mensagens-chave |
| MODELO_DOCUMENTO_PLANEJAMENTO_PROJETO.md | Planejar projetos complexos |
| MODELO_DOCUMENTO_REQUISITOS_PROJETO.md | Detalhar requisitos técnicos |
| MODELO_EAP_TEMPLATE.md | Estruturar decomposição de trabalho |
| MODELO_PROPOSTA_TEMPLATE.md | Criar propostas comerciais |
| RESUMO_PROJETO_TEMPLATE.md | Criar resumo executivo de projeto |
| perfil_contato.md | Registrar contatos individuais |
| pesquisa_de_mercado.md | Conduzir pesquisa de mercado |
| project_brief_template.md | Criar briefing inicial de projeto |
| status_report_template.md | Gerar relatórios de status |
| atas_reuniao_template.md | Template de ata de reunião |
| guia_processo_conceito.md | Guia para documentação de conceitos |
| modelo_contrato_acordo.md | Template de contratos |
| protocolo_tomada_decisao_projeto.md | Padronizar tomada de decisão |
| template_plano_comunicacao_projeto.md | Planejar comunicações de projeto |

**📌 Caso de Uso**: 
- **Workflows Padrão**: Copie templates de Core-Docs para trabalho ativo
- **Workflows Avançados**: Consulte Docs_complementares para casos especiais
- **Customização**: Adapte templates conforme necessário, mas mantenha estrutura base do YAML frontmatter

---

## 🏗️ Componentes-Chave do Framework IDEKnow v2.0

### Pilares da Arquitetura

#### 1️⃣ **Estrutura do Grafo de Conhecimento**
- **Entidades Padronizadas**: Client Profile, Contact, Task, Event, Knowledge Article, Contract, Meeting Notes, Observation
- **Relacionamentos Semânticos**: Regras padronizadas para conectar entidades (cliente → contato → projeto → tarefa)
- **YAML Frontmatter**: Metadados estruturados em todos os documentos para processamento por máquina

#### 2️⃣ **Esquemas e Tipos de Documentos**
Cada tipo de documento tem um schema obrigatório (definido em FR03x_*.md):
- Informações de identificação (ID, criação, modificação)
- Relacionamentos (links para outras entidades)
- Categorização (tags, labels, tipos)
- Propriedades específicas do domínio

#### 3️⃣ **Padrões de Qualidade**
- **Markdown**: Formatação consistente, estrutura hierárquica, legibilidade
- **Nomeação**: Convenções consistentes de arquivo para discoverabilidade
- **Linking**: Estratégia de links internos para criar grafo navegável
- **Tagging**: Sistema de tags para descoberta e filtragem cruzada

#### 4️⃣ **Workflows Padronizados**
- **Reunião**: Agenda → Notas → Decisões → Ações (Rastreáveis)
- **Projeto**: Briefing → Planejamento → Execução → Relatório
- **Cliente**: Perfil → Contato → Projeto → Histórico de Interação

---

## 📊 Distribuição de Conteúdo

| Componente | Quantidade | Propósito |
|-----------|-----------|----------|
| **Diretórios** | 6 principais | Organização por domínio |
| **Subdiretórios** | 10+ | Estrutura hierárquica |
| **Arquivos Markdown** | 65 | Documentação e templates |
| **Esquemas (FR03x)** | 9 | Padrões de documento |
| **Diretrizes (FR0x)** | 8 | Regras e padrões |
| **Templates Reutilizáveis** | 26 | Workflows prontos para uso |

---

## 🚀 Como Usar Este Sistema

### Para Usuários de Primeira Vez
1. **Comece Aqui**: Leia este INDEX para entender a estrutura geral
2. **Conheça o Framework**: Revise `00_meta/FR00_Filosofia Central.md` para entender a filosofia
3. **Escolha um Template**: Navegue para `05_templates/Docs_complementares/` e escolha um template base
4. **Siga o Schema**: Use o schema correspondente de `00_meta/framework_rules/FR03x_*.md`
5. **Adapte e Use**: Customize o template para seu contexto, mantendo a estrutura base

### Para Uso Regular

#### **Iniciando um Novo Projeto**
```
1. Crie um diretório em 02_projects/
2. Copie project_brief_template.md de 05_templates/Docs_complementares/
3. Preencha usando schema FR03 base
4. Vincule a clientes em 01_client/
5. Crie reuniões em 03_meetings/
```

#### **Documentando Reuniões**
```
1. Use 05_templates/Docs_complementares/atas_reuniao_template.md
2. Siga schema FR03b (Atas de Reunião)
3. Armazene em 03_meetings/
4. Registre decisões e ações rastreáveis
```

#### **Criando Novos Templates**
```
1. Identifique o workflow que se repete
2. Use um template existente como base
3. Customize para o caso específico
4. Inclua YAML frontmatter conforme FR03 base
5. Armazene em 05_templates/Docs_complementares/ para reutilização
```

#### **Integrando com IA/Copilot**
```
1. Garanta YAML frontmatter completo em todos os docs
2. Use `.github/copilot-instructions.md` para instruções
3. Forneça contexto de 00_meta/ para agentes de IA
4. Use tags consistentes para melhor recuperação
```

### Dicas de Navegação
- ✅ Use **Cmd+F** (Ctrl+F) para pesquisar por tipo de documento
- ✅ Consulte **00_meta/FR01** para padrões de estrutura de pastas
- ✅ Siga **YAML frontmatter** de FR03 base em todos os novos documentos
- ✅ Verifique **datas de modificação** para encontrar conteúdo atualizado
- ✅ Vincule documentos usando **[[nome_do_arquivo]]** (Obsidian/Logseq syntax)
- ✅ Use **01_client/** para perfis de clientes (singular, não plural)

---

## Statistics

| Directory    | File Count | Purpose                     |
|--------------|------------|-----------------------------|
| 00_meta      | 25         | Framework rules & standards |
| 01_client    | 1          | Client management           |
| 02_projects  | 9          | Project documentation       |
| 03_meetings  | 0          | Meeting notes repository    |
| 04_documents | 4          | Document repository         |
| 05_templates | 26         | Template library            |
| **Total**    | **65**     | **Complete KM System**      |

---

---

## 🔄 Manutenção e Evolução

### Recomendações de Manutenção
- **Revisão**: Revise este INDEX trimestralmente conforme o conteúdo evolui
- **Atualizações**: Adicione/remova seções conforme novos workflows forem identificados
- **Escalabilidade**: Estes padrões crescem com você – novos tipos de documento precisam apenas de novo schema FR03x
- **Melhor Prática**: Mantenha README atualizado em subdiretórios principais

### Extensão do Framework
Para adicionar novo tipo de documento:
1. Crie schema em `00_meta/framework_rules/FR03[letra]_esquema_[tipo].md`
2. Defina campos obrigatórios e recomendados
3. Crie template em `05_templates/Docs_complementares/`
4. Atualize este INDEX
5. Implemente em projetos específicos

---

## 🔗 Integração com Ferramentas Externas

### ✅ Ferramentas Compatíveis
- **Obsidian**: YAML frontmatter + [[wikilinks]] nativo
- **Logseq**: Suporte completo para YAML frontmatter e links
- **GitHub Copilot**: Instruções em `.github/copilot-instructions.md`
- **VS Code**: Configurações otimizadas em `.vscode/settings.json`
- **Knowledge Graph Tools**: Estrutura semântica pronta para export

### 📝 Formato de Dados
- **Markdown**: Legível, versionável, Git-friendly
- **YAML Frontmatter**: Estruturado, processável por máquina
- **Links**: Wiki-style `[[arquivo]]` para navegação
- **Tags**: `#tag` para filtragem cruzada

---

## 📚 Recursos Adicionais

### Documentação do Framework
- `00_meta/FR00_Filosofia Central.md` – Visão teórica do IDEKnow v2.0
- `00_meta/FR03_esquema_base_yaml_frontmatter.md` – Schema obrigatório para todos
- `00_meta/FR05_estrategia_de_links.md` – Como vincular efetivamente
- `00_meta/FR08_dicas_interacao_ia.md` – Prompting e contexto para IA

### Templates Recomendados para Começar
1. **Cliente Novo**: `05_templates/Docs_complementares/perfil_contato.md`
2. **Projeto Novo**: `05_templates/Docs_complementares/project_brief_template.md`
3. **Reunião**: `05_templates/Docs_complementares/atas_reuniao_template.md`
4. **Relatório**: `05_templates/Docs_complementares/status_report_template.md`

---

## 📞 Suporte e Perguntas

### Encontrando Respostas
| Pergunta | Consulte |
|----------|----------|
| Como criar novo documento? | `00_meta/FR03_esquema_base_yaml_frontmatter.md` + tipo específico |
| Qual template devo usar? | Navegue para `05_templates/Docs_complementares/` por tipo |
| Como nomear arquivos? | `00_meta/FR02_convencoes_nomeacao_arquivos.md` |
| Como organizar pastas? | `00_meta/FR01_estrutura_de_pastas.md` |
| Como vincular documentos? | `00_meta/FR05_estrategia_de_links.md` |
| Como usar com IA? | `00_meta/FR08_dicas_interacao_ia.md` + `.github/copilot-instructions.md` |

---

## 📌 Informações de Versão

- **Framework**: IDEKnow v2.0
- **Última Atualização**: 2 de Dezembro de 2025
- **Tipo de Diretório**: Template System + Knowledge Management Framework
- **Idioma**: Português (Brasil)
- **Status**: 🟢 Produção – Pronto para uso

---

## 📋 Arquivos de Configuração Relacionados

- **.github/copilot-instructions.md** – Instruções de IA do GitHub Copilot para esta base de conhecimento
- **.vscode/settings.json** – Configuração do editor VS Code para edição ótima de markdown

---

**Bem-vindo ao seu Sistema de Gestão do Conhecimento! 🚀**

Este framework foi projetado para crescer com você. Comece com um template, domine os padrões e construa uma base de conhecimento poderosa e interconectada.
