---
title: Guia do Processo de Documentação de Conceitos
uuid: "00000000-0000-0000-0000-000000000000" # UUID de exemplo, substitua por um gerado
type: guia
status: rascunho # Padrão para 'rascunho', atualize conforme necessário
created_date: 2025-05-22 # Usando a data de hoje
updated_date: 2025-05-22 # Usando a data de hoje
tags:
- #documentacao
- #conceito
author: "The Good Docs Project"
---

# Guia do Processo de Documentação de Conceitos

## Objetivo
Este documento fornece diretrizes estruturadas para criar documentação de conceitos eficaz, seguindo os padrões do The Good Docs Project. Ele aborda:

- Metodologias de pesquisa
- Melhores práticas de redação
- Estratégias de manutenção

> **Nota**: Para templates e recursos adicionais, visite o [repositório de templates no GitLab](https://gitlab.com/tgdp/templates).

## Antes de escrever um documento de conceito

Antes de começar a trabalhar no seu documento de conceito, siga estes passos preparatórios para garantir um material abrangente e eficaz:

- **Conheça seu público:** Entenda quem é o público-alvo, seu nível de familiaridade com o tema, funções, responsabilidades e necessidades específicas. Isso permitirá adaptar o conteúdo e a linguagem do documento.
- **Mapeie o conceito:** Crie um panorama do conceito, incluindo conexões com outros conceitos, seu lugar no sistema e dependências. Isso ajuda na compreensão e pode servir como recurso visual no documento. Veja a seção [Recurso visual](#crie-recursos-visuais-para-um-documento-de-conceito) abaixo.
- **Explore o histórico do conceito:** Busque informações sobre a origem, contexto e limitações que moldaram o conceito. Converse com desenvolvedores ou gestores de projeto para entender o contexto mais amplo.
- **Defina escopo e limites:** Delimite claramente o que o conceito abrange e o que não abrange, pesquisando informações dentro desses limites.
- **Colete dúvidas e perguntas comuns:** Revise chats internos, sistemas de suporte ou discussões públicas para reunir dúvidas frequentes sobre o conceito. Procure perguntas como "O que é?", "Por que preciso disso?", "Por que não usar {Y}?", "Quando não devo usar?" para antecipar e responder no documento.

## Guia para nomear seu documento de conceito

Há diferença entre o tipo de informação e o título do documento. O tipo geralmente é chamado de Conceito (em GitLab e DITA) ou Explicação (em Diataxis).

Ambos se referem ao mesmo tipo: uma visão geral de um tópico/conceito/funcionalidade para ajudar o usuário a entender ideias complexas e contexto. Neste template, os termos são tratados como sinônimos.

Dentro de um conjunto de documentação, há flexibilidade para nomear títulos. Opções comuns:

- Visão geral de {conceito ou assunto}
- Introdução a {conceito ou assunto}
- Sobre {conceito ou assunto}
- Entendendo {conceito ou assunto}
- Contexto
- Nome do {conceito ou assunto} como substantivo. Exemplo: Pagamentos. (Recomendado pelo GitLab)

Opções menos comuns:

- Curso Rápido
- {conceito ou assunto 101}
- Tour pelo {conceito}

Evite títulos vagos como "Visão Geral" ou "Introdução" sem um substantivo que descreva o tema. Títulos vagos são menos encontráveis.

Para SEO, use títulos descritivos e ricos em palavras-chave que transmitam claramente o tema principal do documento. Isso melhora a encontrabilidade e ajuda mecanismos de busca a entenderem a relevância do conteúdo.

**Nota:** *Não confunda um documento de Conceito (parte da documentação técnica) com outros tipos chamados de 'documento de conceito', como Proposta/RFC ou parte de Game Design Document (GDD).* 

## Escrevendo para públicos variados

Antes de criar o conteúdo, organize o documento para atender diferentes públicos. Use as estratégias abaixo para aumentar a acessibilidade:

- **Identifique categorias de público:** Categorize possíveis públicos, como desenvolvedores, gestores, usuários finais e suporte. Defina personas com diferentes níveis de conhecimento e interesses. Veja exemplo em [The Good Docs Project](../user-personas/process_user-personas.md).
- **Avalie necessidades e objetivos:** Para cada categoria, avalie necessidades, objetivos e expectativas. Entenda como o documento pode atender desafios específicos.
- **Determine relevância setorial:** Reconheça o setor de cada público. Adapte o documento para diferentes contextos, pois cada setor pode exigir abordagens distintas.
- **Função e relação com o conceito:** Entenda o papel de cada público em relação ao conceito (decisor, implementador, apresentador, avaliador) para abordar suas necessidades.
- **Compreensão contextual:** Analise situações de trabalho e problemas enfrentados pelo público. Considere se estão avaliando o conceito, buscando aplicações práticas ou preparando apresentações.

Ao escrever para múltiplos públicos, considere:

- **Fragmentação (chunking):** Divida o documento em seções claras. Cada seção pode atender um público ou aspecto do conceito, facilitando a busca por informações relevantes.
- **Camadas de explicação:** Misture uma explicação simples para leigos e detalhes para técnicos. Comece com uma explicação geral e aprofunde para quem busca mais detalhes, incluindo exemplos, analogias e recursos visuais.
- **Divisão em múltiplos documentos:** Se o conceito for complexo e as informações divergirem muito, crie documentos separados para cada público.

## Escreva um documento de conceito

O processo está descrito no [guia de template](guide_concept.md).

## Crie recursos visuais para um documento de conceito

Recursos visuais são fundamentais para tornar informações complexas mais acessíveis e engajantes.

Incluem diagramas (árvores de decisão, diagramas de contexto, fluxogramas), vídeos curtos, tabelas comparativas e imagens. Escolha elementos que complementem a narrativa e ajudem o leitor a compreender o conceito.

Se optar por diagramas, eles devem mostrar relações entre componentes-chave, dando uma visão geral da estrutura e conexões do conceito.

| Tipo de Diagrama     | Valor                                                       | Quando Usar                                                                           |
| -------------------- | ----------------------------------------------------------- | ------------------------------------------------------------------------------------- |
| Diagrama de Contexto | Mostra componentes do sistema e suas interações.            | Quando ilustrar como o conceito se encaixa em um framework ou ecossistema maior.      |
| Fluxograma           | Representa processos passo a passo e decisões.              | Ideal para explicar procedimentos sequenciais ou decisões dentro do conceito.         |
| Árvore de Decisão    | Mostra cenários de decisão e resultados.                    | Eficaz para apresentar escolhas e consequências relacionadas ao conceito.             |
| Infográfico          | Usa visuais e ícones para transmitir informações complexas. | Bom para visão geral de alto nível, especialmente quando o apelo visual é importante. |

O uso de recursos visuais segue princípios de aprendizagem multimídia, como o [princípio da contiguidade espacial de Mayer](resources_concept.md). Isso significa manter texto e visual próximos e alinhados, evitando sobrecarregar o leitor com informações desconexas.

Vídeos são úteis para demonstrar processos dinâmicos, exemplos reais ou ilustrar a evolução do conceito. Use vídeos com moderação e apenas se agregarem valor, pois podem tirar o leitor do contexto e são caros de produzir/manter. Documentação conceitual muda menos que tutoriais, pois conceitos mudam menos que interfaces.

Vídeos devem ser curtos e objetivos. Considere incluir desenhos estilo quadro branco. Lembre-se que vídeos são difíceis de "escanear" rapidamente.

Ao usar recursos visuais de forma estratégica, a documentação conceitual transmite informações de forma mais eficaz e melhora a compreensão do leitor.

## Mantenha um documento de conceito

Para garantir que o documento permaneça útil e confiável, estabeleça um plano de manutenção. Considere as práticas abaixo:

- **Controle de versão:** Use sistemas como Git para rastrear mudanças e consultar versões anteriores.
- **Revisão regular:** Programe revisões periódicas, especialmente após atualizações no conceito ou surgimento de novos conceitos relacionados.
- **Comunicação com stakeholders:** Mantenha contato com equipes relevantes para garantir informações atualizadas.
- **Feedback de usuários:** Solicite feedback de leitores e partes interessadas para identificar pontos de melhoria.
- **Testes de atualização:** Ao modificar o conceito, valide se as mudanças estão bem representadas. Teste compreensão com técnicas como:
  - **Explique como se fosse para uma criança:** Peça para alguém explicar o conceito com suas palavras.
  - **Cenários reais:** Apresente situações práticas e pergunte como aplicariam o conceito.
  - **Canais de feedback:** Ofereça formulários ou pesquisas para coletar dúvidas e sugestões.
- **Componentes visuais:** Atualize diagramas e visuais sempre que necessário. Use diagramas como código para facilitar a manutenção.
- **Documentação de mudanças:** Exiba a versão do documento e registre alterações. Isso ajuda a entender a evolução do material.

Normalmente, basta incluir um "Última atualização: {Data}" na página, o que pode ser feito pelo seu CMS.

Se versionar, use o padrão MAJOR.MINOR.PATCH.

Exemplo:

| Versão | Data       | Descrição                          |
| ------ | ---------- | ---------------------------------- |
| 2.0    | 2023-06-01 | Adicionada nova limitação          |
| 1.1    | 2023-02-01 | Explicação aprimorada de conceitos |
| 1.0    | 2023-01-01 | Documento de Conceito inicial      |

---

> Explore outros templates em [The Good Docs Project](https://thegooddocsproject.dev/). Use nosso [formulário de feedback](https://thegooddocsproject.dev/feedback/?template=Concept%20process) para enviar sugestões sobre este template.
