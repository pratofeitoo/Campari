---
title: 04_template_relatorio_revisao_projetos_finalizados
short_name: 04_relatorio_revisao_projetos
type:
  - revisão-projetos-concluídos
  - post-mortem
  - lições-aprendidas
status: ativo
version: "2.0"
access_level: interno
author:
  - "[Seu Nome ou ID]"
related_templates:
  - 02_template_planejamento_projeto
  - 02_template_requisitos_projeto
  - 04_template_status_report
tags:
  - project-closure
  - lessons-learned
  - continuous-improvement
created: 2025-06-06T22:52
updated: 2025-12-03T04:08
---
# Relatório de Análise e Revisão de Projeto (Post-Mortem)

## 🎯 Propósito e Contexto

### Por Que Este Documento Existe

Este relatório captura aprendizados valiosos enquanto estão frescos na memória, para que o projeto finalizando traga benefícios contínuos:

- ✅ **Melhorar processos futuros:** Identificar o que funcionou para replicar
- ✅ **Compartilhar conhecimento:** Documentar decisões e trade-offs para outras equipes
- ✅ **Identificar sucessos:** Reconhecer práticas que devem ser padronizadas
- ✅ **Solucionar problemas:** Criar ações concretas para resolver gargalos

### ⏰ Quando Usar Este Template

**Timing Crítico:** Complete **dentro de 2 semanas** após a conclusão ou cancelamento do projeto, enquanto detalhes ainda estão frescos na memória da equipe.

- ✅ Para projetos **concluídos** com sucesso
- ✅ Para projetos **parcialmente bem-sucedidos** 
- ✅ Para projetos **cancelados ou pausados** (lições são ainda mais valiosas)
- ❌ Não use para projetos ainda em andamento

### 👥 Quem Deve Participar

Este documento deve ser preparado de forma **colaborativa**:

- **Facilitador:** Gerente de Projeto (responsável por preencher e coordenar)
- **Participantes Principais:** 40-50% da equipe core (desenvolvedores, designers, analistas)
- **Perspectiva Executiva:** Patrocinador ou diretor (se disponível)
- **Perspectiva Externa:** 1-2 stakeholders (cliente, parceiro)

**Tempo Estimado:**
- Coleta de informações: 30-45 minutos
- Reunião de workshop: 60-90 minutos
- Documentação final: 30 minutos

### 🔗 Como Este Documento Se Integra

Este relatório alimenta sistemas críticos de sua organização:

```
Post-Mortem (este doc)
    ↓
📊 Métricas de desempenho organizacional
📚 Base de conhecimento de lições aprendidas
🎯 Melhoria contínua de processos
👥 Desenvolvimento de competências da equipe
```

---

## 🗺️ Localização neste Vault

**Arquivo:** `04_documents/reports/04_relatorio_revisao_projetos_finalizados.md`

**Documentos Relacionados:**
- 📋 Planejamento: → `02_projects/02_template_planejamento_projeto.md`
- 📊 Requisitos: → `02_projects/02_template_requisitos_projeto.md`
- 📈 Relatórios de Status: → `04_documents/reports/status_report/`

---

## Status do Projeto
- **Status:** [Concluído / Cancelado / Pausado]
- **Data da Revisão:** DD/MM/AAAA

---

## 1. Informações Gerais

| **Campo**              | **Detalhe**                     |
| ---------------------- | ------------------------------- |
| **Nome do Projeto**    | [Insira o Nome]                 |
| **Gerente de Projeto** | [Nome do Gerente]               |
| **Patrocinador**       | [Nome do Executivo/Diretor]     |
| **Data de Início**     | DD/MM/AAAA                      |
| **Data de Conclusão**  | DD/MM/AAAA                      |
| **Equipe Principal**   | [Listar nomes ou departamentos] |

---

## 2. Resumo Executivo

### Definição de Sucesso

Antes de atribuir um veredicto, entenda como sucesso é definido para **este projeto específico**:

| Categoria | Critério de Sucesso |
|-----------|-------------------|
| **Sucesso Total** | ✅ Todas as metas atingidas (KPI ≥ 95%), orçamento ≤ 105%, no prazo (±5 dias) |
| **Sucesso Parcial** | ⚠️ Maioria das metas atingidas (KPI ≥ 80%), orçamento até 120%, atraso < 2 semanas |
| **Falha** | ❌ Menos de 80% das metas atingidas OU cancelamento do projeto |

### Resumo Geral do Projeto

- **Resumo:**
  > Escreva um parágrafo breve (3-5 linhas) descrevendo o resultado final do projeto. Ele foi considerado um sucesso? O produto final foi entregue conforme o esperado?
  > 
  > **Exemplo Bom:** "O projeto de Integração CRM foi concluído em 15 de novembro, com apenas 2 semanas de atraso. Todas as 8 funcionalidades críticas foram entregues e testadas, atingindo 96% de cobertura de requisitos. O orçamento foi 8% acima da previsão devido a retrabalho de qualidade, mas a satisfação do cliente foi excelente (8,5/10)."
  >
  > **Evite:** Descrições genéricas como "foi um bom projeto" ou "conseguimos entregar".

- **Veredito Geral:**
  - [ ] ✅ Sucesso Total
  - [ ] ⚠️ Sucesso Parcial
  - [ ] ❌ Falha

- **Principais Conquistas** (1-3 maiores vitórias):
  - **Exemplo:** "Entrega 2 semanas antes do prazo original"
  - **Exemplo:** "ROI de 340% superior ao projetado"
  - **Exemplo:** "Adoção de 85% dos usuários na primeira semana"

---

## 3. Análise de Escopo e Metas (KPIs)

### O Que Incluir Nesta Seção

Compare o que foi planejado no Project Charter com o que foi efetivamente entregue. Seja específico e mensurável:

- ✅ Cada objetivo deve ter uma **meta quantificável** (não "melhorar" mas "+20%")
- ✅ Resultado real deve ser **número, porcentagem ou status** (não "foi bom")
- ✅ Status deve usar indicadores claros (✅ Superado / ⚠️ Parcial / ❌ Não Atingido)

### Tabela de Análise

| **Objetivo / Entregável** | **Critério de Sucesso (Meta)** | **Resultado Real** | **Status** |
| ------------------------- | ------------------------------ | ------------------ | ---------- |
| Exemplo: Aumentar leads qualificados | +20% de leads qualificados mensais | +25% atingido | ✅ Superado |
| Exemplo: Lançar App v1.0 com features críticas | Todas as 8 features críticas | 7 features entregues + 1 adiada | ⚠️ Parcial |
| Exemplo: Reduzir tempo de resposta | < 2 segundos para 95% das requisições | 1,8 segundos para 97% das requisições | ✅ Superado |
| [Objetivo 4] | [Meta] | [Resultado] | [Status] |

### Interpretação de Variância de Desempenho

| Realização | Interpretação | Ação |
|----------|--------------|------|
| 100%+ (Superado) | Objetivo alcançado ou excedido | Documentar como foi feito para replicar |
| 95-99% (Praticamente Atingido) | Pequena lacuna | Entender por que 5% não foi alcançado |
| 80-94% (Parcialmente Atingido) | Lacuna significativa | Análise de causa raiz necessária |
| < 80% (Não Atingido) | Falha crítica | Deve gerar lição aprendida |

---

## 4. Cronograma e Orçamento

### Cronograma

#### O Que Informar
- Data final planejada vs. data final real
- Variância total (em dias/semanas)
- Causa raiz da variância (não apenas "atraso")

#### Métricas

- **Data de Término Planejada:** DD/MM/AAAA
- **Data de Término Real:** DD/MM/AAAA
- **Desvio (Variância):** [X dias/semanas de atraso ou adiantamento]
- **% de Variância:** [Calcule: (Real - Planejado) / Planejado × 100]
- **Causa Raiz do Desvio:** [Explique brevemente por que houve atraso ou adiantamento]

#### Exemplo de Preenchimento Correto
```
- Data de Término Planejada: 2025-10-31
- Data de Término Real: 2025-11-15
- Desvio: +15 dias de atraso (5% de variância)
- Causa Raiz: Aprovação de stakeholder levou 2 semanas adicionais 
  (identificado na semana 2) + 1 semana de retrabalho de qualidade
```

#### Interpretação de Variância de Cronograma

| Desvio | Interpretação | Ação |
|--------|--------------|------|
| -10% a +5% | Desempenho saudável | Documentar práticas que permitiram ficar no prazo |
| +5% a +15% | Variância aceitável | Investigar causa e registrar aprendizado |
| +15% a +25% | Problema moderado | Lição aprendida necessária |
| >+25% | Problema crítico | Análise de causa raiz obrigatória |

---

### Orçamento (Budget)

#### O Que Informar
- Orçamento aprovado inicial
- Custo real final
- Variância ($ ou %)
- Breakdown de custos (onde foi gasto mais do que planejado?)

#### Métricas

- **Orçamento Planejado:** R$ 0,00
- **Custo Real Final:** R$ 0,00
- **Desvio:** [R$ ou % acima/abaixo do orçamento]
- **% de Variância:** [Calcule: (Real - Planejado) / Planejado × 100]
- **Motivo do Desvio:** [Seja específico: não "despesas imprevisitas" mas "licenças de software custaram R$ X a mais porque precisamos de 2 usuários adicionais"]

#### Exemplo de Preenchimento Correto
```
- Orçamento Planejado: R$ 150.000,00
- Custo Real Final: R$ 162.500,00
- Desvio: +R$ 12.500,00 (+8,3% de variância)
- Motivo do Desvio: 
  • Serviços de consultoria externa: +R$ 8.000 (projeto técnico mais complexo)
  • Licenças adicionais: +R$ 4.500 (2 usuários não previstos)
```

#### Interpretação de Variância de Orçamento

| Desvio | Interpretação | Ação |
|--------|--------------|------|
| -20% a +5% | Desempenho saudável | Documentar boas práticas de controle |
| +5% a +15% | Variância aceitável | Investigar e registrar |
| +15% a +25% | Problema moderado | Lição aprendida necessária |
| >+25% | Problema crítico | Análise de causa raiz obrigatória |

---

## 5. O Que Funcionou Bem? (Pontos Fortes)

### Propósito

Liste as **práticas, ferramentas ou comportamentos que devem ser repetidos** em projetos futuros. O objetivo não é apenas celebrar, mas identificar padrões replicáveis.

### Como Preencer Esta Seção

Para cada ponto forte, tente seguir este padrão:

```
❌ Fraco: "A comunicação foi boa."
✅ Bom: "O standup diário de 10 minutos manteve todos alinhados 
         e identificava bloqueadores em tempo real. Recomendação: 
         Adotar em todos os futuros projetos de desenvolvimento."
```

### Exemplos de Pontos Fortes (Escolha os que se aplicam)

- **Processos & Metodologia:**
  - ✅ Comunicação diária (daily scrum/standup) manteve todos alinhados
  - ✅ Reviews semanais com stakeholders reduziram surpresas e retrabalho
  - ✅ Prototipagem rápida permitiu feedback antes do desenvolvimento
  - ✅ [Adicione seu exemplo específico]

- **Ferramentas & Tecnologia:**
  - ✅ [Nome do software] agilizou [processo específico]
  - ✅ [Ferramenta de colaboração] melhorou [resultado específico]
  - ✅ [Descrição específica do que uma ferramenta permitiu]

- **Equipe & Competências:**
  - ✅ Contratação rápida de especialista em [área] resolveu [problema]
  - ✅ Treinamento prévio em [tecnologia] acelerou desenvolvimento
  - ✅ Cross-funcionalidade entre [times] melhorou qualidade

---

## 6. O Que Não Funcionou? (Desafios)

### Propósito

Liste os **problemas enfrentados, gargalos e falhas**. A regra de ouro: **Foque nos processos, não culpe pessoas**. O objetivo é melhorar o sistema, não punir indivíduos.

### Padrão de Preenchimento

```
❌ Fraco: "O time foi lento em entregar."
✅ Bom: "O processo de aprovação de design foi lento porque 
         (a) não havia SLA de resposta dos stakeholders, 
         (b) ocorriam mudanças não comunicadas, 
         (c) havia múltiplos níveis de aprovação não claramente definidos."
```

### Categorias de Desafios (Organize por tipo)

- **Escopo & Requisitos:**
  - ⚠️ O escopo mudou [número] vezes sem ajuste no prazo
  - ⚠️ Requisitos não eram claros quando o desenvolvimento começou
  - ⚠️ Mudanças de requisitos chegavam sem análise de impacto
  - ⚠️ [Descrição específica do seu desafio]

- **Riscos & Problemas Técnicos:**
  - ⚠️ Um risco técnico previsto se concretizou e não tínhamos plano de mitigação
  - ⚠️ Ambiente de produção teve [problema específico] não testado antes
  - ⚠️ Integração com [sistema externo] foi mais complexa que planejado
  - ⚠️ [Seu desafio técnico]

- **Comunicação & Stakeholders:**
  - ⚠️ Stakeholders demoraram [X semanas] para aprovar [artefato específico]
  - ⚠️ Expectativas entre áreas não foram alinhadas no kickoff
  - ⚠️ Mudanças de prioridade não eram comunicadas à equipe em tempo real
  - ⚠️ [Seu desafio de comunicação]

- **Recursos & Alocação:**
  - ⚠️ Recurso de [especialidade] não estava disponível quando necessário
  - ⚠️ Equipe foi dividida entre [X projetos], reduzindo foco
  - ⚠️ [Seu desafio de recursos]

---

## 7. Lições Aprendidas e Recomendações

### Propósito

Esta é a **seção mais importante para o aprendizado organizacional**. O objetivo não é apenas descrever problemas, mas transformá-los em **mudanças concretas e acionáveis** que melhoram futuros projetos.

### Como Extrair Lições: Técnica dos 5 Porquês

Para cada problema, faça perguntas sucessivas para chegar à causa raiz:

```
Problema: "O projeto atrasou 2 semanas"
  ↓ Por quê? "Porque a aprovação do stakeholder foi lenta"
  ↓ Por quê? "Porque não havia SLA definido de resposta"
  ↓ Por quê? "Porque o stakeholder estava em período de férias/sobrecarregado"
  ↓ Por quê? "Porque não foi reservado tempo no planejamento do projeto"
  ↓ Por quê? "Porque o processo de planejamento não solicita confirmação de disponibilidade"

LIÇÃO RESULTANTE: "Adicionar etapa no kickoff: confirmar disponibilidade 
de todos os stakeholders de aprovação e definir SLA de resposta de 5 dias."
```

### Estrutura de Uma Boa Lição Aprendida

Uma lição aprendida deve ter 3 elementos:

1. **O Problema / Ocorrência**: O que aconteceu?
2. **Impacto Mensurável**: Como isso afetou o projeto? (em dias, %, custo)
3. **A Lição (Ação Concreta)**: O que vamos fazer diferente?

```
❌ Fraco:
| Problema | Impacto | Lição |
| Comunicação ruim | Equipe confusa | Comunicar melhor |

✅ Bom:
| Problema | Impacto | Lição |
| Não havia SLA de aprovação de design | Atraso de 14 dias + retrabalho estimado em 80h | Estabelecer SLA de aprovação de 5 dias com escalação se não aprovado |
```

### Tabela de Lições Aprendidas

| **O Problema / Ocorrência** | **Impacto Mensurável** | **A Lição (Ação Concreta para o Futuro)** |
| --- | --- | --- |
| Ex: Demora na contratação de fornecedor | Atraso de 2 semanas no início do projeto | **Ação:** Iniciar processo de compras 1 mês antes do kickoff oficial. Adicionar como marco crítico no plano inicial. |
| Ex: Falha no servidor de testes (downtime de 2 dias) | Equipe parada por 2 dias, atraso no ciclo de testes | **Ação:** Ter um ambiente de backup pronto antes de qualquer fase de QA. Implementar health checks automatizados. |
| Ex: Requisitos mudaram 3 vezes sem análise de impacto | +15 dias de atraso, retrabalho estimado em 120h | **Ação:** Implementar processo de "Change Control" obrigatório: toda mudança requer análise de impacto no cronograma/orçamento. Gatekeeping por PM. |
| [Insira Problema] | [Mensure em dias/horas/% de retrabalho] | **Ação:** [Recomendação prática e implementável] |

### Priorizando Lições (Se Houver Muitas)

Se extraiu mais de 7 lições, priorize pelo **impacto × probabilidade**:

- 🔴 **Alta Prioridade:** Problemas que custaram >10% de atraso OU podem ocorrer novamente em curto prazo
- 🟠 **Média Prioridade:** Problemas menores ou riscos futuros
- 🟡 **Baixa Prioridade:** Problemas específicos deste projeto, improvável que se repita

---

## 8. Plano de Ação Pós-Projeto

### Tarefas Administrativas de Encerramento

Checklist obrigatório para formalizar o encerramento:

- [ ] **Arquivamento de Documentação:** Todos os artefatos (requisitos, designs, testes, código) archivados em local centralizado e com versão final marcada
- [ ] **Desmobilização de Recursos:** Comunicação formal liberando membros da equipe para novos projetos; atualizar alocações
- [ ] **Comunicação de Encerramento:** E-mail aos stakeholders informando conclusão, entregáveis finais e próximas etapas
- [ ] **Celebração de Sucesso:** Reconhecer publicamente as conquistas da equipe (reunião, email, documento)
- [ ] **Atualização de Base de Conhecimento:** Adicionar lições aprendidas ao sistema de conhecimento organizacional
- [ ] **Feedback de 360 Graus:** Coletar feedback da equipe, stakeholders e clientes (formulário rápido)
- [ ] **Lições no Sistema:** Vincular lições aprendidas a processos/templates para implementação em futuros projetos

### Ações Derivadas de Lições Aprendidas

Para cada lição aprendida da Seção 7 que requer ação organizacional, complete:

| **Lição Aprendida** | **Ação a Executar** | **Responsável** | **Prazo** | **Status** |
| --- | --- | --- | --- | --- |
| (Do Seção 7) SLA de aprovação não definido | Criar template de "Stakeholder Engagement Plan" com SLA explícito | [Nome] | 2025-12-31 | ⏳ Pendente |
| (Do Seção 7) Ambiente de backup não existia | Provisionar ambiente de QA redundante; documentar procedimento | [Nome] | 2026-01-15 | ⏳ Pendente |
| [Sua lição] | [Qual ação ela gera?] | [Quem?] | [Data limite] | [Status] |

---

## ⚡ Guia Prático de Preenchimento

### Opção 1: Post-Mortem Rápido (15 minutos)

Para projetos menores ou quando tempo é limitado, complete **apenas**:
- Seção 1: Informações gerais
- Seção 2: Resumo executivo e veredicto
- Seção 5-6: Um ponto-chave funcionou bem, um ponto não funcionou
- Seção 7: As TOP 3 lições aprendidas (mais impactantes)

**Ideal para:** Projetos internos, features pequenas, sprints

---

### Opção 2: Post-Mortem Completo (90 minutos)

Complete todas as seções com detalhe:
- Análise completa de KPIs
- Análise detalhada de cronograma e orçamento
- 5-8 pontos fortes e desafios
- 5-7 lições aprendidas estruturadas
- Plano de ação completo

**Ideal para:** Projetos com clientes, releases importantes, iniciativas estratégicas

---

### 📋 Roteiro Recomendado para Preenchimento

#### **Antes da Reunião de Post-Mortem** (30 minutos)
1. Gerente de Projeto coleta dados:
   - Datas: planejado vs. real
   - Orçamento: aprovado vs. gasto
   - KPIs: metas vs. realizado
   - Riscos que se materializaram
   - Feedback inicial da equipe

#### **Durante da Reunião de Post-Mortem** (60-90 minutos)

1. **Aquecimento (5 min):** Recapitular o que o projeto foi/fez
2. **Resumo Executivo (5 min):** Rápido voto de qual foi o veredicto
3. **Análise Quantitativa (15 min):** Revisar cronograma, orçamento, KPIs
4. **O Que Funcionou (10 min):** Brainstorm dos 3-5 pontos fortes
5. **O Que Não Funcionou (10 min):** Brainstorm dos 3-5 desafios
6. **Lições & Causas Raiz (25 min):** Para cada desafio, aplicar "5 Porquês" e chegar à lição
7. **Ações & Ownership (10 min):** Para lições, designar responsável e prazo

#### **Depois da Reunião** (30 minutos)
1. PM finaliza documento com notas
2. Circula para revisão rápida da equipe (feedback inline)
3. Salva em local padrão: `04_documents/reports/[nome_projeto]/04_relatorio_...md`

---

### ✅ Checklist de Qualidade Antes de Finalizar

- [ ] **Clareza:** Nenhuma sentença genérica (tudo é específico e mensurável)
- [ ] **Completude:** Todas as 8 seções preenchidas (mesmo que breve para Opção Rápida)
- [ ] **Inclusão:** Toda lição aprendida tem uma "Ação" clara associada
- [ ] **Números:** Variâncias de cronograma e orçamento têm % calculados
- [ ] **Responsabilidade:** Plano de Ação tem nomes atribuídos (não "alguém vai fazer")
- [ ] **Rastreabilidade:** Cada lição vincula a um desafio/problema na Seção 6
- [ ] **Profissionalismo:** Sem culpa pessoal, foco em processos melhoráveis

---

### 🎓 Dicas Finais para Sucesso

> **Reúna a equipe:** Não preencha isso sozinho. Faça uma reunião (ou série de conversas) com o time para colher feedbacks honestos. Post-mortems são experiências de aprendizado coletivo, não documentos individuais.

> **Crie Segurança Psicológica:** Deixe claro desde o início que o objetivo é analisar **processos**, não buscar culpados. Normalize admitir erros e dizer "não sabíamos na época". As melhores lições vêm de falhas honestas.

> **Seja Específico:** Evite generalizações:
> - ❌ "a comunicação foi ruim"
> - ✅ "os e-mails semanais não eram lidos pela liderança porque não havia tempo marcado na agenda para revisão"

> **Quantifique o Impacto:** Transforme "isso causou problema" em "isso custou 10 dias de atraso":
> - ❌ "Requisitos mudaram bastante"
> - ✅ "Requisitos mudaram 4 vezes (semanas 2, 4, 6 e 8), gerando 3 dias de retrabalho cada = 12 dias de impacto total"

> **Seja Acionável:** Toda lição aprendida deve gerar uma ação concreta:
> - ❌ "Precisamos comunicar melhor"
> - ✅ "Implementar daily standup obrigatório de 10 minutos das 9:30-9:40 com agenda padrão (bloqueadores/progresso)"

---

