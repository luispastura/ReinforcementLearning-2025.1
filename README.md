# 🥋 Modelagem de Decisões no Jiu-Jitsu Competitivo usando MDP

## 📌 Descrição do Projeto
Este projeto apresenta uma modelagem matemática para auxiliar atletas e treinadores de Jiu-Jitsu na tomada de decisões estratégicas durante competições, utilizando Processos de Decisão Markovianos (MDP).

## 🎯 Objetivos
- Desenvolver estratégias ótimas baseadas em dados.
- Combinar as regras oficiais da IBJJF com probabilidades e hierarquia posicional para decisões táticas eficientes.
- Oferecer uma ferramenta analítica para atletas melhorarem seu desempenho competitivo.

## 📖 O que é MDP?
Processos de Decisão Markovianos (MDP) são métodos matemáticos que modelam situações de tomada de decisão onde resultados são parcialmente aleatórios e parcialmente sob controle de um decisor.

## Componentes principais:
- **Estados (S)**: posições específicas no combate (ex.: Montada, Guarda Fechada).
- **Ações (A)**: movimentos possíveis (ex.: Passar Guarda, Finalizar).
- **Transições (P)**: probabilidades de mudanças entre estados após ações.
- **Recompensas (R)**: pontos obtidos e melhoria da posição após ações.

## 📌 Hierarquia Posicional
Cada posição possui um valor estratégico definido:

| Posição | Valor |
|---------|-------|
| Controle de Costas | 1.5 |
| Montada | 1.3 |
| Guarda Aberta | 1.0 |
| Meia Guarda | 0.7 |
| Guarda Fechada | 0.3 |
| Embaixo | -0.5 |

## 🛠️ Algoritmos Utilizados
- **Value Iteration**: Encontra valores ótimos iterativamente com menor custo computacional por iteração.
- **Policy Iteration**: Alterna avaliação e melhoria da política, obtendo soluções com menos iterações totais.

## Desempenho dos Algoritmos
| Método | Iterações | Tempo Total | Tempo/Iteração |
|--------|-----------|-------------|----------------|
| Value Iteration | 47 | 3.3 ms | 0.07 ms |
| Policy Iteration | 3 | 1.6 ms | 0.53 ms |

## 🚀 Resultados e Aplicações
## Estratégias Ótimas Identificadas:
- **Posições Dominantes**: Maximizar finalizações.
- **Posições Inferiores**: Priorizar raspagens e defesas eficazes.

## Implicações Práticas:
- Auxilia atletas a focarem em posições estratégicas e reverterem desvantagens rapidamente.
- Favorece a tomada de decisão baseada em dados e estatísticas comprovadas.

## 🧭 Próximos Passos
- Validação empírica com estratégias reais de atletas.
- Refinamento contínuo de parâmetros com dados históricos.
- Expansão com inclusão de novas posições (ex.: "Joelho na barriga").

## 📁 Estrutura do Projeto
- `MDP_Jiu_Jitsu_final_finalissimo.ipynb`: Notebook principal contendo o código e as análises detalhadas.
- Apresentação em PDF com a explicação detalhada dos conceitos, metodologias e resultados.

## 📌 Autoria e Referências
**Projeto desenvolvido por Luis, Bernardo e Lucca.**

Baseado nas regras oficiais da IBJJF e nos conceitos fundamentais de Processos de Decisão Markovianos.

---

**Projeto desenvolvido com foco na aplicação prática e eficiência analítica para atletas de alto desempenho no Jiu-Jitsu Competitivo.**

