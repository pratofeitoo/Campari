---
title: Modelo de Documento de Estrutura Analítica do Projeto (EAP)
uuid: xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx
type: template
status: rascunho
created_date: 2025-05-22
updated_date: 2025-05-22
author: "[Seu Nome/ID]"
tags:
  - template
  - eap
  - gestao-de-projetos
version: "1.0"
access_level: interno
---

<!--
Modelo: Documento de Estrutura Analítica do Projeto (EAP)
Origem: Pasta de Modelos de Documentação
Finalidade: Fornecer uma estrutura clara e consistente para documentar a EAP de um projeto, seguindo as diretrizes de Qualidade & Estrutura de Conteúdo Markdown FR04.
-->

# Estrutura Analítica do Projeto (EAP) – `[Nome do Projeto]`

Este modelo fornece uma estrutura padronizada para documentar a Estrutura Analítica do Projeto (EAP). Substitua todos os campos entre colchetes (ex: `[Nome do Projeto]`) pelas informações específicas do projeto. Siga as diretrizes de formatação e qualidade de conteúdo descritas na FR04.

**Nome do Projeto:** `[Insira o nome completo do projeto]`

**Versão do Documento:** `[ex: 1.0, Rascunho C]`

**Data de Preparação:** `[AAAA-MM-DD]`

**Preparado por:** `[Seu Nome/Departamento]`

**Gerente do Projeto:** `[Nome do Gerente do Projeto]`

## 1. Introdução & Finalidade

Este documento descreve a Estrutura Analítica do Projeto (EAP) para **`[Nome do Projeto]`**. A EAP é uma decomposição hierárquica de todo o escopo de trabalho a ser realizado pela equipe do projeto para atingir os objetivos e criar os entregáveis necessários.

A finalidade desta EAP é:

- Definir o escopo do projeto em termos de componentes de trabalho gerenciáveis.
- Fornecer uma base para planejamento detalhado, estimativas, cronograma e controle de custos.
- Garantir que todo o trabalho necessário está identificado (Regra dos 100%: todo o trabalho dentro do escopo está incluído, nada extra).
- Facilitar a atribuição clara de responsabilidades.
- Servir de base para relatórios de progresso e medição de desempenho.

## 2. Referência de Escopo

Esta EAP baseia-se no escopo do projeto definido nos seguintes documentos:

- **Termo de Abertura / Business Case:** `[Link ou referência ao Termo/Business Case]`
- **Escopo do Trabalho (SOW) / Documento de Requisitos:** `[Link ou referência ao SOW/Requisitos]`

## 3. Referência do Dicionário da EAP

Descrições detalhadas de cada elemento da EAP (especialmente os pacotes de trabalho no nível mais baixo), incluindo responsável, critérios de aceitação, dependências e esforço/duração estimados, podem ser encontradas no **Dicionário da EAP**:

- **Localização do Dicionário da EAP:** `[Link ou referência ao Dicionário da EAP]`

*Nota: Para projetos menores, detalhes resumidos podem ser incluídos diretamente na representação da EAP abaixo, mas recomenda-se um dicionário separado para maior clareza em projetos maiores.*

## 4. Representação da EAP

A EAP pode ser representada em vários formatos. Escolha o(s) formato(s) mais adequado(s) ao contexto do seu projeto.

### 4.1 Formato de Lista Hierárquica (Visão em Outline)

Este formato usa indentação para mostrar a hierarquia. O esquema de numeração (ex: 1.1, 1.1.1) fornece identificadores únicos para cada elemento.

- **1.0 `[Nome do Projeto]`** (Nível 1 – Projeto Geral)
  - **1.1 `[Fase Principal ou Entregável 1, ex: Gestão do Projeto]`** (Nível 2)
    - **1.1.1 `[Subentregável ou Pacote de Trabalho, ex: Planejamento]`** (Nível 3 – Pacote de Trabalho)
    - **1.1.2 `[Subentregável ou Pacote de Trabalho, ex: Monitoramento da Execução]`** (Nível 3 – Pacote de Trabalho)
    - **1.1.3 `[Subentregável ou Pacote de Trabalho, ex: Relatórios]`** (Nível 3 – Pacote de Trabalho)
    - **1.1.4 `[Subentregável ou Pacote de Trabalho, ex: Encerramento]`** (Nível 3 – Pacote de Trabalho)
  - **1.2 `[Fase Principal ou Entregável 2, ex: Definição de Requisitos]`** (Nível 2)
    - **1.2.1 `[Subentregável ou Pacote de Trabalho, ex: Workshops com Stakeholders]`** (Nível 3)
    - **1.2.2 `[Subentregável ou Pacote de Trabalho, ex: Documentação de Requisitos]`** (Nível 3 – Pacote de Trabalho)
    - **1.2.3 `[Subentregável ou Pacote de Trabalho, ex: Aprovação dos Requisitos]`** (Nível 3 – Pacote de Trabalho)
  - **1.3 `[Fase Principal ou Entregável 3, ex: Design]`** (Nível 2)
    - **1.3.1 `[Subentregável, ex: Design de Arquitetura]`** (Nível 3)
      - **1.3.1.1 `[Pacote de Trabalho, ex: Definir Stack Tecnológico]`** (Nível 4 – Pacote de Trabalho)
      - **1.3.1.2 `[Pacote de Trabalho, ex: Criar Diagrama de Arquitetura]`** (Nível 4 – Pacote de Trabalho)
    - **1.3.2 `[Subentregável, ex: Design UI/UX]`** (Nível 3)
      - **1.3.2.1 `[Pacote de Trabalho, ex: Desenvolver Wireframes]`** (Nível 4 – Pacote de Trabalho)
      - **1.3.2.2 `[Pacote de Trabalho, ex: Criar Mockups]`** (Nível 4 – Pacote de Trabalho)
  - **1.4 `[Fase Principal ou Entregável 4, ex: Desenvolvimento]`** (Nível 2)
    - **1.4.1 `[Subentregável ou Pacote de Trabalho, ex: Desenvolvimento da Funcionalidade A]`** (Nível 3 – Pacote de Trabalho)
    - **1.4.2 `[Subentregável ou Pacote de Trabalho, ex: Desenvolvimento da Funcionalidade B]`** (Nível 3 – Pacote de Trabalho)
    - **1.4.3 `[Subentregável ou Pacote de Trabalho, ex: Integração]`** (Nível 3 – Pacote de Trabalho)
  - **1.5 `[Fase Principal ou Entregável 5, ex: Testes]`** (Nível 2)
    - **1.5.1 `[Subentregável ou Pacote de Trabalho, ex: Testes Unitários]`** (Nível 3 – Pacote de Trabalho)
    - **1.5.2 `[Subentregável ou Pacote de Trabalho, ex: Testes de Integração]`** (Nível 3 – Pacote de Trabalho)
    - **1.5.3 `[Subentregável ou Pacote de Trabalho, ex: Testes de Aceitação do Usuário (UAT)]`** (Nível 3 – Pacote de Trabalho)
  - **1.6 `[Fase Principal ou Entregável 6, ex: Implantação]`** (Nível 2)
    - **1.6.1 `[Subentregável ou Pacote de Trabalho, ex: Preparar Plano de Implantação]`** (Nível 3 – Pacote de Trabalho)
    - **1.6.2 `[Subentregável ou Pacote de Trabalho, ex: Executar Implantação]`** (Nível 3 – Pacote de Trabalho)
    - **1.6.3 `[Subentregável ou Pacote de Trabalho, ex: Suporte Pós-Implantação]`** (Nível 3 – Pacote de Trabalho)

*Continue detalhando as fases/entregáveis em pacotes de trabalho menores e gerenciáveis. O nível mais baixo representa um pacote de trabalho.*

### 4.2 Formato Tabular

Este formato é útil para adicionar mais detalhes diretamente, embora a hierarquia possa ser menos óbvia sem atenção à estrutura do ID da EAP.

| ID EAP    | Descrição                      | Nível | ID Pai EAP | Entregável? | Pacote de Trabalho? | Observações / Responsável (Opcional) | Estimativa (Opcional) |
| :-------- | :----------------------------- | :---- | :--------- | :---------- | :------------------ | :----------------------------------- | :-------------------- |
| **1.0**   | **`[Nome do Projeto]`**        | 1     | -          | Sim         | Não                 | Projeto Geral                        |                       |
| **1.1**   | **`[Fase/Entregável 1]`**      | 2     | 1.0        | Sim         | Não                 |                                      |                       |
| 1.1.1     | `[Pacote de Trabalho 1.1.1]`   | 3     | 1.1        | Não         | Sim                 | `[ex: GP]`                           | `[ex: 40h]`           |
| 1.1.2     | `[Pacote de Trabalho 1.1.2]`   | 3     | 1.1        | Não         | Sim                 | `[ex: GP]`                           | `[ex: 80h]`           |
| **1.2**   | **`[Fase/Entregável 2]`**      | 2     | 1.0        | Sim         | Não                 |                                      |                       |
| 1.2.1     | `[Subentregável/Pacote 1.2.1]` | 3     | 1.2        | Sim/Não     | Sim                 | `[ex: Analista]`                     | `[ex: 60h]`           |
| 1.2.2     | `[Pacote de Trabalho 1.2.2]`   | 3     | 1.2        | Não         | Sim                 | `[ex: Analista]`                     | `[ex: 30h]`           |
| **1.3**   | **`[Fase/Entregável 3]`**      | 2     | 1.0        | Sim         | Não                 |                                      |                       |
| **1.3.1** | **`[Subentregável 1.3.1]`**    | 3     | 1.3        | Sim         | Não                 |                                      |                       |
| 1.3.1.1   | `[Pacote de Trabalho 1.3.1.1]` | 4     | 1.3.1      | Não         | Sim                 | `[ex: Arquiteto]`                    | `[ex: 20h]`           |
| 1.3.1.2   | `[Pacote de Trabalho 1.3.1.2]` | 4     | 1.3.1      | Não         | Sim                 | `[ex: Arquiteto]`                    | `[ex: 16h]`           |
| ...       | ...                            | ...   | ...        | ...         | ...                 |                                      |                       |

*Preencha a tabela conforme a decomposição do projeto.*

## 5. Premissas & Observações

- `[Liste premissas específicas feitas durante a criação desta EAP, ex: premissas sobre tecnologia disponível, habilidades dos recursos, etc.]`
- `[Adicione observações relevantes, ex: terminologia específica utilizada, nível de detalhamento escolhido.]`
- Os elementos do nível mais baixo (Pacotes de Trabalho) representam partes discretas de trabalho que podem ser atribuídas, estimadas e acompanhadas.

## 6. Histórico de Revisões

| Versão      | Data           | Autor(es) | Resumo das Alterações        |
| :---------- | :------------- | :-------- | :--------------------------- |
| `[ex: 0.1]` | `[AAAA-MM-DD]` | `[Nome]`  | `[ex: Rascunho Inicial]`     |
| `[ex: 1.0]` | `[AAAA-MM-DD]` | `[Nome]`  | `[ex: Versão base aprovada]` |
|             |                |           |                              |

---

**Fim do Documento EAP**
