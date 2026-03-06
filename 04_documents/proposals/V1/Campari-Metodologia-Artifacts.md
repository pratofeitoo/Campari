---
created: 2026-03-06T17:15
updated: 2026-03-06T17:17
---
# ARTEFATOS COMPLEMENTARES DA PROPOSTA: CAMPARI

## Resumo das Modificações da Proposta (Summary)
- **Objetivos convertidos para SMART**: estabelecidos baselines e métricas palpáveis atreladas a turnover (20% -> 14%), qualificação contratual (attrition <4%) e metas de engajamento interno (aumento de 10-15%).
- **Detalhamento do Orçamento**: especificação individual de módulos base contra banco de horas estimadas, incluindo a adição recomendada de 10% do orçamento em Contingência de flutuação de tempo.
- **Delimitação de Escopo e Entregáveis**: lista de saídas tangíveis mapeada formatando explicitamente itens *out-of-scope*.
- **Conformidade em Termos e LGPD**: criação da via ready para elaboração de minutas de serviço resguardando responsabilidades e destituição das bases de raw records após 30 dias.

---

## 1. Gap Matrix (Matriz de Lacunas Originais Identificadas)

| Gap (Problema) | Impact | Recomendação / Solução | Owner (Resp.) | Estimativa Esforço |
|---|---|---|---|---|
| Objetivos sem métricas (Apenas retóricos) | High | Formatar SMART, adicionar prazos (12 meses) baselines e percentuais de target. | PM (DiverC.) | M |
| Entregáveis vagos ou sem formato específico | High | Incluir tabela explicitando formato e critério de aprovação/QA para cada fase. | Delivery Lead | S |
| Ausência de exclusões de escopo explícitas | Medium | Adicionar seção *Out-Of-Scope* prevenindo mal entendidos na fase de execução (Hunting, Jurídico etc). | Sales/PM | S |
| Orçamento flat sem proteção de escopo (contingência) | Medium | Adicionar Contingency buffer de 10% no somatório por demanda. | PM / VP | S |
| Risco Trabalhista/Legal Pessoal & LGPD não mapeado | High | Incorporar cláusula base de anonimização restrita a dados estatísticos em pesquisas sob exclusão ativa (30 dias). | Legal | M |

---

## 2. RACI de Implantação

| Fase / Milestone | PM DiverCidade | Sponsor Campari / RH | Lideranças (Participantes) | Legal / IT Campari |
|---|---|---|---|---|
| Aprovação e Preenchimento Documentos e Dados | C | A/R | I | C |
| Execução do Diagnóstico de Maturidade | R/A | C | C | I |
| Relatório de Diagnóstico & Aprovação | R | A/C | I | C |
| Workshops de Cultura e Capacitação Liderança | R | I | C | I |
| Manutenção e Reuniões Mensais PMO (Mestrado) | R | A | C | I |

*(R = Responsible, A = Accountable, C = Consulted, I = Informed)*

---

## 3. Risk Log (Registro de Riscos e Mitigação)

| Risco Descritivo                                                                    | Probabilidade | Impacto | Estratégia de Mitigação                                                                                                      | Dono do Risco    |
|-------------------------------------------------------------------------------------|---------------|---------|------------------------------------------------------------------------------------------------------------------------------|------------------|
| Baixo comparecimento nas sessões de Diagnóstico ou Workhsops de Cultura e Liderança | Medium        | High    | Convocação Endorsed pela alta direção. Realização de make-up sessions para faltantes.                                        | Sponsor Campari  |
| Demora ou embaraço à liberação de PII ou Dados Demográficos pelo setor de TI        | Medium        | High    | Fornecimento antecipado de termos (NDAs) com o compliance e garantir modelo agregado de extração evitando exposição cruzada. | Legal/IT Campari |
| Burn Rate alto de horas da consultoria nos dois primeiros meses não deixando saldo  | Medium        | Medium  | Track-record e dashboard semanal na fase de Assessment para balanço financeiro visível da contingência.                      | PM DiverCidade   |

---

## 4. Timeline (Macro)

```csv
milestone_id,fase,nome_entregavel,prazo,responsavel
1,Diagnostico,diagnostic_report_v1.pdf,Semana 4,DiverCidade
2,Planejamento,roadmap_strategic_v1.pptx,Semana 6,DiverCidade
3,Capacitacao,training_deck.pdf,Semana 24,DiverCidade
4,Consolidacao,cultural_framework.pdf,Semana 36,DiverCidade
5,Fechamento,final_report.pdf,Semana 48,DiverCidade
```

---

## 5. Replication Guide (Runbook Operacional)

**Fase 1: Assessment / Setup Técnico**
- Kick-off Interno agendado (Semana 1): validar pontos de comunicação para coletas do assessment.
- Executar onboarding das contas e disparar convites de NDA/LGPD.
- Requisitar extrato nominal (Data dump de turnover segmentado da base geral).

**Fase 2: Execução de Consultoria e Liderança**
- Disparar agenda de convites mensais de Capacity Planning.
- Reservar horas da liderança sênior (DiverCidade) e aplicar o *diagnostic_report*.
- Apresentar baseline da pesquisa contra benchmark CPG & Bebidas.

**Fase 3: Reporting & Cobrança**
- Criar folder de entrega para o "monthly_report".
- Registrar Timesheet contendo as horas trabalhadas na primeira e última semana do mês corrente.
- Emitir a NF juntamente como Extrato de Horas do mês para a contabilidade Campari, referenciando eventual abatimento da Contingência.
