# Distribuição de Gumbel

Este repositório contém uma análise estatística utilizando a **Distribuição de Gumbel**. O código foi desenvolvido para simular, estimar parâmetros e realizar testes de hipótese relacionados à distribuição, além de gerar gráficos e realizar análises de simulação.

## Descrição

A distribuição de Gumbel, também conhecida como distribuição do valor extremo de tipo I, é usada para modelar o maior ou o menor valor de uma amostra aleatória. É frequentemente aplicada em áreas como análise climática, confiabilidade de sistemas e séries temporais.

O código desenvolvido aborda diversos aspectos dessa distribuição:

1. **Definição e visualização da função densidade**: A função densidade de probabilidade da distribuição de Gumbel é plotada para diferentes parâmetros.
2. **Geração de amostras**: Utiliza o método de transformação inversa para gerar amostras de uma distribuição Gumbel.
3. **Estimativas de parâmetros**: Através da maximização da função log-verossimilhança, o código estima os parâmetros da distribuição.
4. **Simulações**: Realiza simulações para avaliar o viés, erro quadrático médio (EQM) e variância das estimativas, variando o tamanho da amostra.
5. **Intervalos de confiança**: Calcula intervalos de confiança assintóticos para os parâmetros e verifica a proporção de vezes que o intervalo cobre o valor verdadeiro.
6. **Testes de hipótese**: Avalia o erro tipo I de um teste de hipótese para a distribuição Gumbel.

## Dependências

O código utiliza as seguintes bibliotecas R:

- `evd` — Para trabalhar com distribuições extremas.
- `optimx`, `ucminf`, `minqa` — Para otimização e ajuste dos parâmetros.
  
## Resultados

O código realiza simulações para diversos tamanhos de amostra, avaliando a precisão das estimativas dos parâmetros da distribuição de Gumbel. Além disso, calcula o erro tipo I de testes de hipótese sobre a média e a variância da distribuição.

## Gráficos

O código gera gráficos que mostram o comportamento da função densidade de probabilidade da distribuição de Gumbel para diferentes parâmetros, além de gráficos que comparam o erro quadrático médio (EQM) e o viés das estimativas para diferentes tamanhos de amostra.

## Conclusões

Os resultados obtidos com as simulações ajudam a entender o comportamento da distribuição de Gumbel em relação à estimativa dos parâmetros e à precisão das estimativas em função do tamanho da amostra.



Este `README.md` descreve o que o código faz e as dependências necessárias, sem mencionar que é um trabalho de disciplina.
