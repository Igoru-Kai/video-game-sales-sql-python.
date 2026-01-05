# 🎮 Análise de Performance: A Guerra dos Consoles (2001-2015)

[![Abrir no Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252)](https://colab.research.google.com/drive/1npBvjpcuoBX2BK4yWbyJuxU_jJdWxZvr?usp=sharing)

Este projeto apresenta um estudo sobre a dinâmica competitiva entre **Sony, Nintendo e Microsoft**. Através de uma abordagem híbrida entre **Python** e **SQL**, a análise explora o volume de vendas globais, taxas de crescimento relativo e a distribuição de sucesso comercial na indústria de jogos.

## 📌 Destaques do Projeto

* **Ambiente Relacional:** Migração de dados de arquivos flat (`.csv`) para um banco de dados relacional `SQLite` dentro do fluxo de análise.
* **Tratamento de Dados:** Implementação de técnicas de *Forward Fill* e *Backward Fill* para correção de séries temporais e tratamento de valores ausentes (NAs).
* **Normalização Estatística:** Uso de **Base Indexada (1.0)** para equalizar o ponto de partida de empresas com portes diferentes, permitindo comparar a real velocidade de expansão.
* **Vetorização NumPy:** Categorização de sucesso comercial (*Super Hits*) utilizando lógica de `np.where` aninhada para alta performance em grandes volumes de dados.

## 📊 Estrutura da Análise

### 1. Evolução Macroeconômica
Contextualização do volume total de software vendido globalmente para estabelecer a linha de base do mercado antes de segmentar por fabricante.

### 2. Guerra dos Consoles (Maturidade vs. Expansão)
Uma comparação entre o **Volume Bruto** e a **Velocidade de Crescimento**:
* **Sony & Nintendo:** Líderes em faturamento absoluto, enfrentando barreiras de crescimento devido à maturidade de suas bases já estabelecidas.
* **Microsoft:** Demonstrando a maior aceleração proporcional do período, atuando como o elemento de "quebra de monopólio" ao entrar no mercado.

### 3. Distribuição "Do Fracasso ao Super Hit"
Segmentação científica da indústria para provar a tese da **Cauda Longa**:
* **Super Hits (Top 1%):** Títulos com vendas $\ge 10M$ que sustentam o ecossistema.
* **Cauda Longa:** A vasta maioria dos lançamentos que, embora fundamentais para a variedade do catálogo, possuem menor escala comercial individual.

## 🛠️ Tecnologias Utilizadas
* **Linguagem:** Python 3.x
* **Manipulação de Dados:** `Pandas`, `NumPy`
* **Banco de Dados:** `SQLite3` (SQL Puro para agregação de dados)
* **Visualização:** `Seaborn`, `Matplotlib`

---

## 👨‍💻 Autor

**Igor Vinicius**
