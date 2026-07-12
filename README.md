# Pacote de Replicação - Revisão Sistemática de Escopo sobre LLMs no Teste de Software

Este repositório contém o pacote de replicação da revisão sistemática de escopo intitulada:
**"Revisão Sistemática de Escopo sobre Aplicações de Large
Language Models no Teste de Software"**

Autores, instituição, afiliação, contato e local foram omitidos para revisão double-blind.

O objetivo deste pacote de replicação é apoiar a transparência, a reprodutibilidade e a verificação do protocolo da revisão e de seus artefatos intermediários.

---

## Estrutura do Repositório

```text
replication-package/
|-- 00_all_search_results.csv
|-- 01_after_deduplication.csv
|-- 02_screened_title_abstract_50.csv.csv
|-- 03_full_text_review_final_16.csv.csv
|-- Planilha_Extracao_LLMs_Teste_Software  - Planilha_Extracao_LLMs_Teste_Software (1).csv
`-- README.md
```

### 00_all_search_results.csv (1378 records)

Todos os registros retornados pelas buscas nas bases IEEE Xplore e ACM Digital Library, incluindo duplicatas.

### 01_after_deduplication.csv (1321 records)

Conjunto após a remoção de duplicatas.

### 02_screened_title_abstract_50.csv.csv (50 records)

Registros selecionados após a triagem por título e resumo.

### 03_full_text_review_final_16.csv.csv (16 records)

Conjunto final de registros revisados em texto completo e utilizados na síntese da revisão.

### Planilha_Extracao_LLMs_Teste_Software  - Planilha_Extracao_LLMs_Teste_Software (1).csv (16 records)

Planilha de extração e mapeamento dos estudos em relação às questões de pesquisa.

---

## Estratégia de Busca

Bases consultadas: IEEE Xplore e ACM Digital Library

Period: 2020-2025

Campos: título, resumo e termos-chave

String de busca:

```text
("Large Language Model" OR LLM OR "Generative AI" OR ChatGPT OR "Foundation Model")
AND
("Software Testing" OR "Test Generation" OR "Test Case" OR "Test Automation" OR "Bug Repair" OR "AI-assisted testing")
```

---

## Protocolo de Triagem

### Critérios de Inclusão

- CI1 - Artigo primário revisado por pares
- CI2 - Publicado entre 2020 e 2025
- CI3 - Texto completo disponível
- CI4 - Uso de LLMs aplicado ao Teste de Software
- CI5 - Apresenta avaliação, proposta ou experimento

### Critérios de Exclusão

- CE1 - Estudos secundários, como surveys, revisões sistemáticas da literatura ou mapeamentos
- CE2 - Não relacionados a Teste de Software
- CE3 - Texto completo indisponível
- CE4 - Não utilizam LLMs
- CE5 - Duplicatas ou versões estendidas

---

## Assistência de IA e Automação

Algumas etapas foram auxiliadas por ferramentas de IA, incluindo normalização da string de busca, apoio à triagem e organização dos dados. As decisões finais foram tomadas manualmente pelos autores.

---

## Citação

Autores omitidos para revisão double-blind. (2025). *Large Language Models in Software Testing: A Scoping Review*.

---

## Contato

Contato omitido para revisão double-blind.

---

## Situação

Revisão concluída. Pacote de replicação disponível para revisão double-blind.
