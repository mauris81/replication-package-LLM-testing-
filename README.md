# Replication Package – Scoping Review on LLMs for Software Testing

This repository contains the full replication package for the Scoping Review titled:
**“Revisão Sistemática de Escopo sobre Aplicações de LLMs no Teste de Software”**  
(V&V 2025 – Universidade Federal de Lavras)

The goal of this replication package is to ensure transparência, reprodutibilidade e verificabilidade de todas as etapas do protocolo adotado na revisão.

---

## Repository Structure

replication-package-LLM-testing/  
├── 00_all_search_results.csv  
├── 01_after_deduplication.csv  
├── 02_screened_title_abstract_50.csv  
├── 03_full_text_review_final_18.csv  
├── search_strings/  
│   ├── ieee_xplore_search.txt  
│   ├── acm_dl_search.txt  
├── prompts/  
│   ├── screening_prompts_used.txt  
└── README.md  

### 00_all_search_results.csv (1378 registros)  
Contém todos os registros retornados pelas buscas nas bases IEEE Xplore e ACM Digital Library, incluindo duplicatas.

### 01_after_deduplication.csv (1321 registros)  
Conjunto após remoção de duplicatas.

### 02_screened_title_abstract_50.csv (50 registros)  
Artigos que passaram no screening de título e resumo.

### 03_full_text_review_final_18.csv (18 registros)  
Conjunto final de artigos incluídos na revisão.

---

## Search Strategy

Bases consultadas: IEEE Xplore e ACM Digital Library  
Período: 2020–2025  
String de busca utilizada:

("Large Language Model" OR LLM OR "Generative AI" OR ChatGPT OR "Foundation Model")  
AND  
("Software Testing" OR "Test Generation" OR "Test Case" OR "Test Automation" OR "Bug Repair" OR "AI-assisted testing")

Strings completas estão na pasta `search_strings/`.

---

## Screening Protocol

### Critérios de Inclusão (CI)
CI1 — Artigo primário revisado por pares  
CI2 — Publicado entre 2020 e 2025  
CI3 — Texto completo disponível  
CI4 — Uso de LLMs aplicado ao Teste de Software  
CI5 — Apresenta avaliação, proposta ou experimento  

### Critérios de Exclusão (CE)
CE1 — Estudos secundários (surveys, SLRs, mappings)  
CE2 — Não relacionados a Teste de Software  
CE3 — Sem texto completo  
CE4 — Não utilizam LLMs  
CE5 — Duplicatas / versões estendidas  

---

## AI Assistance and Automation

Algumas etapas foram auxiliadas por IA (ChatGPT), incluindo normalização da search string, apoio ao screening e organização. As decisões finais foram tomadas manualmente pelos autores.

---

## Citation

Marshall, R., & Neves, M. M. R. (2025).  
Replication Package – Scoping Review on LLMs for Software Testing.  
GitHub Repository.

---

## Contact

Ruby Marshall — ruby.marshall@estudante.ufla.br  
Maurício Magri Ribas das Neves — mauricio.neves@estudante.ufla.br  

---

## Status

Revisão concluída. Pacote de replicação completo.
