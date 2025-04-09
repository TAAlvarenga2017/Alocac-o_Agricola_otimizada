# 🌾 Alocação Otimizada de Culturas Agrícolas com Algoritmos Evolutivos

Este projeto aplica algoritmos evolutivos, especificamente o **NSGA-II**, para resolver um problema real de **alocação de culturas agrícolas em propriedades rurais**, considerando múltiplos objetivos:

- 💰 Maximizar o lucro
- 💧 Minimizar o consumo de água
- 🔄 Respeitar regras de rotação de culturas
- 🌤️ Considerar a adaptabilidade climática das culturas

---

## 🚀 Objetivo

Desenvolver um modelo de otimização multiobjetivo que proponha a melhor alocação de culturas agrícolas por talhão, balanceando os interesses econômicos, ambientais e agronômicos do produtor rural.

---

## 🧠 Técnicas Utilizadas

- Algoritmo Genético Multiobjetivo **NSGA-II** (via [pymoo](https://pymoo.org/) ou implementação própria)
- Representação cromossômica: vetor com códigos de cultura por talhão
- Avaliação multiobjetivo com 3 funções:
  - `f1`: lucro total (maximizar)
  - `f2`: volume total de água utilizada (minimizar)
  - `f3`: penalização por quebra de rotação (minimizar)

---
## 📦 Fontes de Dados
                     
 - Rentabilidade por cultura(CONAB / Embrapa / SEBRAE)
- Necessidade hídrica(Embrapa, universidades agrícolas)
- Compatibilidade climática(INMET / ClimaTempo)
- Regras de rotação(Embrapa / literatura técnica)
- Áreas da propriedade(Dados simulados ou baseados na realidade)
--- 

## 📈 Resultados Esperados

Conjunto de soluções de Pareto: lucro vs água

Gráfico de alocação otimizada por talhão

Relatórios em .xlsx ou .pdf

Interface para simulação (Streamlit)

---
## 📌 Status do Projeto
🚧 Em desenvolvimento. Próximos passos:

 Adicionar dados reais

 Integrar com mapa via folium ou plotly

 Publicar demo via Streamlit Cloud
 
----

### 📚 Referências
Deb, K. et al. (2002) — A Fast and Elitist Multiobjective Genetic Algorithm: NSGA-II

pymoo: Multi-objective optimization in Python (https://pymoo.org)

Embrapa e CONAB — Dados agronômicos de referência

---
## 🤝 Contribuições
Sinta-se livre para abrir issues, enviar pull requests ou propor melhorias. Toda colaboração é bem-vinda! 🌱

## 🧑‍💻 Autor
Taís Aparecida Alvarenga — Cientista de Dados em transição para Engenharia de Dados com foco em IA aplicada à agropecuária.
