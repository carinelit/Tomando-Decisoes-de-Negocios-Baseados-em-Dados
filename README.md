# Business Decisions Based on Data - A/B Test & Hypothesis Prioritization

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=python&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat&logo=scipy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

## Sobre o projeto

Projeto de tomada de decisoes de negocio baseadas em dados para uma grande loja online. Combina priorizacao de hipoteses com frameworks ICE e RICE e analise completa de Teste A/B para identificar qual variacao gera maior receita e conversao. Projeto desenvolvido no Bootcamp de Analise de Dados da TripleTen Brasil.

## Perguntas de negocio

- Quais hipoteses de crescimento de receita devem ser priorizadas?
- - O grupo B do teste A/B apresenta melhor conversao que o grupo A?
  - - A diferenca no tamanho medio do pedido entre os grupos e estatisticamente significativa?
    - - Qual decisao tomar com base nos resultados: encerrar o teste ou continuar?
     
      - ## Estrutura do projeto
     
      - ### Parte 1 - Priorizacao de Hipoteses
     
      - - Aplicacao do framework ICE (Impact x Confidence / Effort)
      - - Aplicacao do framework RICE (Reach x Impact x Confidence / Effort)
      - - Comparacao entre os dois rankings com visualizacao grafica
      - - Conclusao sobre qual framework usar e por que
             
      - ### Parte 2 - Analise do Teste A/B
             
      - - Receita acumulada e tamanho medio de pedido por grupo
      - - Diferenca relativa na conversao acumulada (Grupo B vs Grupo A)
      - - Calculo de percentis 95 e 99 para deteccao de anomalias
      - - Grafico de dispersao de precos dos pedidos
      - - Testes de significancia estatistica nos dados brutos e filtrados
      - - Decisao final fundamentada com base nos resultados
                         
      - ## Principais insights
                         
      - - Framework RICE reordena significativamente as hipoteses em relacao ao ICE por considerar o alcance
      - - O grupo B apresenta diferenca estatisticamente significativa na conversao
      - - Apos filtragem de outliers e contaminados, os resultados se mantiveram consistentes
      - - Decisao final: encerrar o teste com o grupo B como lider
                                 
       - ## Datasets utilizados
                                 
      - | Arquivo | Descricao |
      - | `hipoteses_nos.csv` | 9 hipoteses com Reach, Impact, Confidence e Effort |
      - | `pedidos_eua.csv` | Log de pedidos com grupo A/B, receita e data |
      - | `visitas_nos.csv` | Registros de visitas por grupo e data |
                                 
      - ## Stack utilizada
                                 
      - - Python 3
      - - Pandas - manipulacao e limpeza de dados
      - - Matplotlib / Seaborn - visualizacao de graficos
      - - SciPy - testes de significancia estatistica (Mann-Whitney)
      - - Jupyter Notebook
                                           
      - ## Como executar
                                           
      - ```bash
      git clone https://github.com/carinelit/Tomando-Decisoes-de-Negocios-Baseados-em-Dados
      cd Tomando-Decisoes-de-Negocios-Baseados-em-Dados
      jupyter notebook
      ```

      ## Portfolio

      [linkedin.com/in/carinelitwinczuk](https://www.linkedin.com/in/carinelitwinczuk)
