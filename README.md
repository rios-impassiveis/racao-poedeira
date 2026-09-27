# 🐔 Ração da Poedeira

Calculadora simples para formulação de ração para galinhas poedeiras, com cálculo de quantidade dos ingredientes, custo do lote e planejamento de consumo.

## 🌐 Acessar a calculadora

👉 **[Abrir Ração da Poedeira](https://rios-impassiveis.github.io/racao-poedeira/)**

A calculadora funciona diretamente no navegador, sem necessidade de instalação.

## ✨ Recursos

- 🐣 **4 fases de criação**
  - Inicial
  - Crescimento
  - Postura
  - Terminação
- ⚖️ Cálculo automático da quantidade de cada ingrediente em kg
- 💰 Estimativa do custo do lote
- 📦 Cálculo do custo por kg e por saco
- 📊 Visualização da composição da ração
- 🐔 Planejador de consumo por número de aves, consumo diário e período
- 📝 Ingredientes e percentuais editáveis
- 💾 Salvamento das alterações no navegador
- 📋 Copiar a receita em formato de texto
- 📱 Interface adaptada para celulares

## 🧮 Como funciona

A quantidade de cada ingrediente é calculada proporcionalmente à soma dos percentuais informados:

> **kg do ingrediente = (% do ingrediente ÷ soma dos %) × total do lote**

Isso permite trabalhar mesmo quando a soma dos percentuais não estiver exatamente em 100%.

## 💰 Preços

A calculadora apresenta preços de referência em reais por kg. Esses valores podem ser alterados diretamente pelo usuário para refletir os preços de sua região.

## ⚠️ Observação

As faixas de idade, consumo diário e alertas de cálcio e núcleo são referências gerais para consulta rápida.

A dosagem do núcleo deve seguir sempre as orientações do fabricante. Para ajustes de proteína, energia e demais parâmetros nutricionais, recomenda-se consultar um profissional habilitado.

## 🛠️ Tecnologia

Projeto desenvolvido como uma aplicação web estática utilizando:

- HTML
- CSS
- JavaScript
- `localStorage`
- GitHub Pages

Não há necessidade de servidor ou banco de dados para utilizar a calculadora.

## 📂 Estrutura

```text
racao-poedeira/
├── index.html
└── README.md
