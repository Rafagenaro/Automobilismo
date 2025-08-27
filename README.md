# Análise Exploratória de Dados - Concessionária de Veículos

Este projeto tem como objetivo realizar uma Análise Exploratória de Dados (EDA) em um dataset automotivo, contendo especificações técnicas de diversos modelos de carros.  
A análise busca identificar os principais fatores que impactam o preço dos veículos, auxiliando a equipe de vendas e marketing a definir estratégias de precificação e destacar atributos mais valorizados pelos clientes.

---

## Dataset

O dataset contém variáveis relacionadas às características estruturais, mecânicas e de desempenho dos veículos.  

Principais colunas:  
- `make` → fabricante do carro  
- `fuel-type` → tipo de combustível  
- `aspiration` → tipo de aspiração (normal/turbo)  
- `num-of-doors` → número de portas  
- `body-style` → estilo da carroceria (sedan, hatchback, convertible etc.)  
- `drive-wheels` → tipo de tração (fwd, rwd, 4wd)  
- `wheel-base`, `length`, `width`, `height` → dimensões  
- `curb-weight` → peso do veículo  
- `engine-type` e `num-of-cylinders` → especificações do motor  
- `engine-size` → tamanho do motor  
- `horsepower` → potência do motor  
- `city-mpg` e `highway-mpg` → consumo de combustível (cidade/estrada)  
- `price` → preço do veículo (variável-alvo)  

---

## Ferramentas e Bibliotecas

A análise foi conduzida em **Python 3.x**, utilizando:  

- **Pandas** → manipulação e limpeza dos dados  
- **NumPy** → cálculos numéricos  
- **Matplotlib** e **Seaborn** → visualizações  
- **Jupyter Notebook** → desenvolvimento da análise  

---

## Etapas da Análise

1. Carregamento e inspeção dos dados  
2. Estatísticas descritivas e distribuições  
3. Análise univariada e multivariada  
4. Correlação entre variáveis  
5. Visualizações para identificar padrões de preço  
6. Extração de insights principais  

---

## Principais Insights

- O **tamanho do motor (engine-size)** apresentou forte correlação positiva com o preço dos veículos.  
- A **potência (horsepower)** também foi um dos fatores determinantes para preços mais altos.  
- O **estilo de carroceria (body-style)** impacta significativamente no valor: modelos **hardtop** e **convertible** possuem preços médios mais elevados, enquanto **hatchbacks** tendem a ser os mais baratos.  
- Veículos mais **largos (width)** e mais **pesados (curb-weight)** também mostraram tendência de preços superiores.  
- O **consumo de combustível (city-mpg e highway-mpg)** tem correlação negativa com o preço: carros mais econômicos geralmente são mais baratos.  

---
