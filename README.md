# Pacote de Replicação - Revisão Sistemática de Escopo sobre LLMs no Teste de Software

Este repositório contém o pacote de replicação da revisão sistemática de escopo intitulada:
**"Revisão Sistemática de Escopo sobre Aplicações de Large Language Models no Teste de Software"**

**Autores:** Ruby Marshall e Maurício Magri Ribas das Neves  
**Instituição:** Universidade Federal de Lavras (UFLA) — Câmpus São Sebastião do Paraíso, MG, Brasil  
**Contato:** ruby.marshall@estudante.ufla.br | mauricio.neves@estudante.ufla.br  
**Disciplina:** Verificação e Validação (VV 2025)

O objetivo deste pacote de replicação é apoiar a transparência, a reprodutibilidade e a verificação do protocolo da revisão e de seus artefatos intermediários.

---

## Estrutura do Repositório

```text
replication-package/
|-- 00_all_search_results.csv
|-- 01_after_deduplication.csv
|-- 02_screened_title_abstract_47.csv
|-- 03_full_text_review_final_12.csv
|-- 04_planilha_extracao_LLMs_teste_software  - planilha_extracao_LLMs_teste_software.csv
`-- README.md
```

### 00_all_search_results.csv (1378 records)

Todos os registros retornados pelas buscas nas bases IEEE Xplore e ACM Digital Library, incluindo duplicatas.

### 01_after_deduplication.csv (1321 records)

Conjunto após a remoção de 57 duplicatas.

### 02_screened_title_abstract_47.csv (47 records)

Artigos potencialmente relevantes após a triagem por título, resumo e palavras-chave (1274 registros excluídos nesta etapa).

### 03_full_text_review_final_12.csv (12 records)

Conjunto final de 12 estudos primários incluídos na revisão, após a leitura completa (35 estudos excluídos nesta etapa).

### 04_planilha_extracao_LLMs_teste_software  - planilha_extracao_LLMs_teste_software.csv (12 records)

Planilha de extração: mapeamento dos 12 estudos primários em relação às questões de pesquisa (QP1 - aplicações, QP2 - desafios, QP3 - oportunidades), incluindo a coluna com a LLM utilizada em cada estudo.

---

## Protocolo de Seleção (resumo)

| Etapa | Registros |
|-------|-----------|
| Identificação (busca) | 1378 |
| Duplicatas removidas | 57 |
| Após deduplicação | 1321 |
| Excluídos na triagem (título/resumo) | 1274 |
| Potencialmente relevantes | 47 |
| Excluídos na leitura completa | 35 |
| **Estudos primários incluídos** | **12** |

---

## Estratégia de Busca

Bases consultadas: IEEE Xplore e ACM Digital Library. Período: 2020-2025. Campos: título, resumo e palavras-chave.

String de busca:

```text
("Large Language Model" OR LLM OR "Generative AI" OR ChatGPT OR "Foundation Model")
AND
("Software Testing" OR "Test Generation" OR "Test Case" OR "Test Automation" OR "Bug Repair" OR "AI-assisted testing")
```

---

## Critérios de Inclusão e Exclusão

Inclusão: CI1 artigo primário revisado por pares; CI2 publicado entre 2020 e 2025; CI3 texto completo disponível; CI4 uso de LLMs aplicado ao Teste de Software; CI5 apresenta avaliação, proposta ou experimento.

Exclusão: CE1 estudos secundários (surveys, SLRs, mapeamentos); CE2 não relacionados a Teste de Software; CE3 texto completo indisponível; CE4 não utilizam LLMs; CE5 duplicatas ou versões estendidas.

---

## Assistência de IA e Automação

Algumas etapas foram auxiliadas por ferramentas de IA, incluindo normalização da string de busca, apoio à triagem e organização dos dados. As decisões finais foram tomadas manualmente pelos autores.

---

## Citação e Contato

MARSHALL, R.; NEVES, M. M. R. das. **Revisão Sistemática de Escopo sobre Aplicações de Large Language Models no Teste de Software**. Universidade Federal de Lavras (UFLA), Câmpus São Sebastião do Paraíso, 2025.

Dúvidas sobre o protocolo ou os artefatos: ruby.marshall@estudante.ufla.br | mauricio.neves@estudante.ufla.br

---

## Situação

Revisão concluída. Pacote de replicação público e disponível para consulta e replicação.
