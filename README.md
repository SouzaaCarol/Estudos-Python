# 📚 estudos python

Este repositório contém uma coleção de estudos e projetos em Python, abrangendo desde fundamentos da linguagem até análise e pré-processamento de dados com bibliotecas populares como Pandas, NumPy, Seaborn e Plotly, além de introdução a Machine Learning com o pipeline do Scikit-learn.

Os estudos estão organizados por tópicos, conforme o conteúdo explorado nos notebooks.

## 📊 Análise e Pré-processamento de Dados

Os códigos demonstram habilidades em carregar, explorar, limpar e preparar dados para análise e modelagem.

### ⚓ Análise_Preditiva_de_Dados_com_Machine_Learning (dataset do Titanic)


Estudo focado na exploração e visualização do famoso dataset do Titanic.

| Tópico | Bibliotecas Utilizadas | Descrição |
| :--- | :--- | :--- |
| **Exploração Inicial** | `pandas`, `seaborn` | Carregamento do dataset, verificação de formato (`shape`), exibição das primeiras linhas (`head()`) e informações gerais (`info()`). |
| **Visualização de Dados** | `plotly.express`, `seaborn`, `matplotlib.pyplot` | Geração de gráficos de pizza para distribuição de sobreviventes e gráficos de contagem (`countplot`) para analisar a sobrevivência por sexo e classe social (`pclass`). |
| **Engenharia e Limpeza de Atributos** | `pandas` | Criação de novas colunas como `family_size` e `is_alone`, e remoção de colunas com ruído ou redundância para preparação do modelo. |
| **Pré-processamento com Pipeline** | `sklearn.pipeline`, `sklearn.compose`, `sklearn.impute`, `sklearn.preprocessing` | Início da construção de um *Pipeline* para automatizar o pré-processamento de dados numéricos (imputação com mediana e escalonamento) e categóricos, preparando os dados para um futuro modelo de Machine Learning. |

### 💳 Arquivo_Inicial_Analise_de_Dados (Analise de Cartão de Crédito)

Estudo de caso para analisar o cancelamento de cartões de crédito (*Churn*), utilizando um dataset de clientes de banco.

| Tópico | Bibliotecas Utilizadas | Descrição |
| :--- | :--- | :--- |
| **Carregamento e Limpeza** | `pandas` | Montagem do Google Drive, leitura do arquivo CSV (`ClientesBanco.csv`), remoção de colunas irrelevantes (`CLIENTNUM`) e tratamento de valores ausentes (`dropna()`). |
| **Exploração Estatística** | `pandas` | Verificação do tipo de dados (`info()`) e exibição de estatísticas descritivas básicas (`describe().round(1)`). |
| **Análise de Churn** | `pandas`, `plotly.express` | Cálculo da quantidade e proporção de clientes cancelados versus clientes ativos (`value_counts()`). Geração de histogramas para diversas colunas, coloridos pela categoria "Cliente" / "Cancelado", para identificar padrões e características que levam ao *churn*. |

## 💻 Fundamentos de Python

Estudos focados nos principais conceitos e estruturas de dados da linguagem Python.

### 📚 Dicionários (Dictionaries)

Demonstração de como trabalhar com dicionários:

- **Criação e Acesso**: Definição de dicionários e acesso a valores por chave.
- **Modificação**: Adição de novos pares chave-valor.
- **Iteração**: Percorrer pares chave-valor (`items()`) e apenas chaves (`keys()`).
- **Dicionários Aninhados**: Exemplo de estrutura de dados complexa.

### 🛠️ Funções em Python

Estudo sobre a criação e uso de funções:

- **Funções Simples**: Definição e chamada de funções sem argumentos.
- **Funções com Parâmetros**: Uso de argumentos para tornar as funções dinâmicas.
- **Funções com Retorno (`return`)**: Demonstração de funções que devolvem valores (retorno único e múltiplo).
- **Argumentos Opcionais**: Definição de valores padrão para parâmetros.

### 🔄 Acumuladores e Contadores

Exemplos práticos de uso de acumuladores (`sum`) e contadores (`count`) em loops de repetição, incluindo:

- Contagem simples.
- Acumulação (soma) simples.
- Contagem e Acumulação com condições (`if`).
- Exemplo de entrada de usuário (`input`) para definir o limite de contagem.

### 📜 Listas e Tuplas

Exploração das estruturas de dados sequenciais:

- **Criação e Acesso**: Definição de listas e tuplas, e acesso a elementos por índice.
- **Operações em Listas**: Adição de itens (`append`, `+`, `extend`), criação de listas vazias e iteração (`for`).
- **Compreensão de Lista**: Uso da sintaxe concisa para criar listas (`[x**2 for x in range(1, 11)]`).
- **Fatiamento (Slicing)**: Acesso a subconjuntos de listas.
- **Tuplas**: Demonstração de sua imutabilidade, concatenação e desempacotamento.

### 🎲 Valores Aleatórios (`random`)

Uso do módulo `random` para gerar valores aleatórios:

- **Geração**: Números aleatórios de ponto flutuante (`random()`, `uniform()`) e inteiros (`randint()`).
- **Seleção**: Escolha aleatória de um item em uma lista (`choice()`).
- **Manipulação de Listas**: Embaralhamento de listas (`shuffle()`) e seleção de múltiplas amostras (`sample()`).
- **Exemplo Prático**: Simulação de um sorteio, onde os números sorteados são removidos de uma lista.

### 💻 Sistema de Cadastro (Biblioteca)

Um projeto que integra vários conceitos de Python para criar um sistema de gerenciamento básico de biblioteca.

| Funcionalidade | Conceitos Utilizados | Descrição |
| :--- | :--- | :--- |
| **Estrutura** | Listas, Dicionários, Funções | Utiliza uma lista (`biblioteca`) para armazenar dicionários (cada um representando um livro). |
| **Funções** | `def` | Funções definidas para `adicionar_livro()`, `verificar_disponibilidade()`, `listar_livros()` e `remover_livro()`. |
| **Interação** | `input()`, `print()`, `while True`, `if/elif/else` | Implementação de um menu interativo para o usuário. |

---

## 🚀 Próximas Atualizações

As futuras atualizações para este repositório podem incluir:

- **Avançar no Projeto Titanic:** Conclusão do pipeline de pré-processamento e implementação de modelos de Machine Learning para prever a sobrevivência.
- **Modelagem de Churn:** Aplicação de algoritmos de classificação para prever a propensão de cancelamento de clientes de cartão de crédito.
- **Desenvolvimento de um Chatbot:** Implementação de um **chatbot simples** utilizando fundamentos de Python e, potencialmente, bibliotecas de Processamento de Linguagem Natural (PLN).
- Novos projetos e aprofundamento em tópicos de Data Science e Machine Learning.
