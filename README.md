# 🗺️ Análise da Rede de Hotéis e Aeroporto de Natal/RN

**Aluno:** Gustavo Pereira de Carvalho

- 📄 [Artigo no Medium](https://medium.com/@hframe032/análise-da-rede-de-hotéis-e-aeroportos-em-natal-rn-666f47dcc86a)  
- 🎧 [Podcast](https://notebooklm.google.com/notebook/bdf9420b-b352-4728-8d79-07daa042ac46/audio)  

---

## 📚 Contextualização

Este repositório faz parte da **segunda atividade da segunda unidade** da disciplina de **Algoritmos e Estruturas de Dados 2**.  

A atividade desenvolvida utiliza **teoria dos grafos**, combinada com dados geográficos da biblioteca **OSMnx**, da linguagem **Python**, para analisar a **acessibilidade entre hotéis e o aeroporto de Natal/RN**.  

Para isso, foi construída uma **MST (Minimum Spanning Tree)**, a fim de identificar as **rotas mais curtas entre os pontos de interesse**, conectando o aeroporto aos hotéis, com o objetivo de **minimizar a distância total** entre eles.  

O desenvolvimento do projeto tem como base um **notebook Jupyter**, que serviu para o cálculo das rotas entre os pontos de interesse, um **artigo no Medium**, que descreve todo o desenvolvimento e explica o funcionamento do código de forma mais detalhada, além de um **podcast gerado pelo NotebookLM**, que aborda o conteúdo do artigo na forma de uma conversa dinâmica, com perguntas e respostas.

---

## 🗂️ Organização

O repositório conta com uma pasta `src`, que contém o **notebook utilizado para o projeto**, com comentários e observações.  

Além disso, na pasta `img` é possível encontrar as **imagens geradas**, neste caso, o **mapa criado pelo programa**.

---

## 🧠 Implementação

O desenvolvimento do programa em **Python** se deu a partir de um **notebook base**, disponibilizado pelo professor **Ivanovitch Silva**.  

A partir desse notebook, foram feitas **pequenas alterações para adaptá-lo aos novos pontos de interesse**, além de alguns ajustes no formato do gráfico de saída.  

Foram utilizadas ferramentas de **LLM (Gemini 2.5 Pro)** para consultar funções das bibliotecas utilizadas, como **OSMnx** e **NetworkX**, porém **não foram feitas mudanças significativas com auxílio dessas ferramentas**.  

Outro uso de ferramentas de IA se deu na **criação do podcast**, que utiliza a ferramenta **NotebookLM** para gerar uma conversa a partir do **artigo disponível no Medium**.

---

## 📊 Resultados

A partir do código criado, foi possível **extrair o grafo da rede viária de Natal/RN** e, por meio das funções das bibliotecas **NetworkX** e **OSMnx**, foram extraídos os **pontos de interesse**, neste caso, **hotéis e aeroporto**.  

Com os dados organizados, foram aplicadas técnicas para **extrair as menores rotas que conectassem todos os pontos de interesse**.  

Para isso, foi utilizada uma **MST criada com o Algoritmo de Kruskal**.  

Um **mapa final com todas as rotas e pontos de interesse foi plotado utilizando o Matplotlib**:

📍 `img/MapaKruskal.png`

---

Em uma análise rápida dos resultados, podemos notar a **concentração de pontos de hospedagem próximos da costa**, o que era esperado, dado o **alto interesse turístico nas praias da cidade**.  

No entanto, a **distância entre esses pontos e o aeroporto**, que é o **principal ponto de entrada e fluxo de turistas**, traz uma **preocupação em relação às rotas até os pontos de concentração de hotéis**, como:  
- 🚧 **Possíveis gargalos nas rotas de acesso**  
- 🏗️ **Necessidade de manutenção preventiva**, a fim de evitar que essas rotas fiquem **temporariamente inacessíveis**

Há ainda a possibilidade de **expandir o trabalho para outros pontos de interesse, possivelmente turísticos, como bares, restaurantes e casas de show**, permitindo assim um **planejamento de rotas personalizadas para turistas e visitantes.**

---

## ✅ Fim

