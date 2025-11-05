# 📊 Análise Exploratória de Dados (EDA) - Desempenho Escolar

## 📋 Sumário do Projeto

Este projeto consiste em uma Análise Exploratória de Dados (EDA) realizada na linguagem R, utilizando o ecossistema `tidyverse`, para entender os fatores que influenciam o desempenho de estudantes em testes padronizados (Matemática, Leitura e Escrita).

O objetivo é identificar padrões, correlações e diferenças significativas entre grupos demográficos e educacionais, fornecendo *insights* que podem ser úteis para a tomada de decisões pedagógicas.

---

## 🛠️ Tecnologias e Ferramentas

* **Linguagem:** R
* **Ambiente:** RStudio
* **Pacotes Principais:**
    * `tidyverse` (para manipulação e visualização de dados)
    * `readr` (para importação de CSV)
    * `knitr` (para geração do Notebook)

## 📁 Estrutura do Repositório

* `analise_desempenho.Rmd`: O R Markdown/Notebook contendo todo o código de ETL (Extração, Transformação e Carga), limpeza, análise e visualização.
* `dados/students.csv`: Arquivo de dados brutos utilizado na análise.
* `output/`: Contém os gráficos gerados e exportados em formato PNG/JPEG.

## 🎯 Principais Perguntas de Negócio

1.  Qual é a média de desempenho por nível de educação parental?
2.  Existe uma correlação significativa entre as notas de Leitura e Escrita?
3.  Qual grupo (gênero, grupo de almoço) apresenta a maior taxa de aprovação?

---

## 📈 Resultados e Insights Chave

*(Substitua esta seção com seus achados reais após rodar a análise.)*

Após a análise exploratória, os seguintes *insights* se destacaram:

1.  **Influência Parental:** [Descreva o que você descobriu sobre a educação dos pais. Ex: "Estudantes cujos pais têm Ensino Superior completo apresentaram uma média de notas [X]% superior aos demais."]
2.  **Taxa de Aprovação:** [Descreva o que você descobriu com a sua nova coluna `status_aprovacao`. Ex: "O grupo feminino apresentou uma taxa de aprovação [X]% maior em comparação com o grupo masculino."]
3.  **Correlação:** [Fale sobre a relação entre as variáveis. Ex: "Foi observada uma correlação de [r-value] entre as notas de Leitura e Escrita, indicando que o desempenho em uma é forte preditora da outra."]

*(Você pode adicionar capturas de tela dos seus gráficos mais importantes aqui para um apelo visual!)*

## 🚀 Como Executar o Projeto Localmente

1.  **Clone o Repositório:**
    ```bash
    git clone [https://docs.github.com/pt/migrations/importing-source-code/using-the-command-line-to-import-source-code/adding-locally-hosted-code-to-github](https://docs.github.com/pt/migrations/importing-source-code/using-the-command-line-to-import-source-code/adding-locally-hosted-code-to-github)
    ```
2.  **Abra no RStudio:** Abra o arquivo `.Rproj` (se houver) ou inicie o RStudio e navegue até a pasta do projeto.
3.  **Instale os Pacotes:** Certifique-se de ter o `tidyverse` instalado:
    ```R
    install.packages("tidyverse")
    ```
4.  **Execute a Análise:** Abra o arquivo `analise_desempenho.Rmd` e clique no botão **Knit** (Compilar) para executar toda a análise e gerar o relatório final (HTML/PDF).

---
