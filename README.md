O texto à seguir tem como base o README de Alex Souza com os contatos do mesmo ao final.

# Business Intelligence

O termo Business Intelligence (BI), inteligência de negócios, refere-se ao processo de coleta, organização, análise, compartilhamento e monitoramento de informações que oferecem suporte a gestão de negócios. É o conjunto de teorias, metodologias, processos, estruturas e tecnologias que transformam uma grande quantidade de dados brutos em informação útil para tomadas de decisões estratégicas. ([mais...](https://medium.com/blog-do-zouza/deepening-into-data-warehouse-2900f49faa2))

-----------
# Dicas
- [Análise de Dados](https://medium.com/blog-do-zouza/data-analysis-27a0a3a310a1)
- [Cultura de Dados](https://medium.com/blog-do-zouza/data-driven-organizations-concept-tips-and-a-short-guide-44070f5eed25)
- [ETL](https://blogdozouza.wordpress.com/bi/etl/) (*Extract Transform Load*)
- [Modelagem Multidimensional](https://medium.com/blog-do-zouza/deepening-into-data-warehouse-2900f49faa2)
- [Power BI](https://blogdozouza.wordpress.com/bi/microsoft/power-bi/)
  - Apresentação sobre Dados, Modelagem Dimensional, Ferramentas, Power BI e Ciência de Dados ([Youtube](https://www.youtube.com/watch?v=BgaZ7TrpWsk))
  - [Licença](https://blogdozouza.wordpress.com/2020/03/04/licenciamento-do-power-bi/) 
  - [Dicas rápidas](https://www.instagram.com/alexsouzamsc/) (BI e Machine Learning)
  - Exemplos
    - [Coronavirus](https://app.powerbi.com/view?r=eyJrIjoiOGY3ZWYxNmQtNWY4OC00NGEwLTlhYTUtMDQ2NDZjMjJhOWI1IiwidCI6IjBjNzE1Yjc3LTNmNjktNDY2NC05NmM0LWI0Yjc2MTI0OTk1YSJ9)
    - [Censo Escolar 2020](https://app.powerbi.com/view?r=eyJrIjoiODJmNGY3YzctNGRhOC00MWMwLWI0YWQtNDE2NWViMzc0ZmNhIiwidCI6Ijc5YmY2Y2FlLWMwZWEtNGMzOS04ODgzLWVkNzIzY2Y1NTQ5MiJ9)
    - [Análise Exploratória de Dados](https://blogdozouza.wordpress.com/2021/03/28/censo-escolar-analise-exploratoria-de-dados-aed/)
- [Tableau](https://blogdozouza.wordpress.com/bi/tableau/)
- Lakehouse ([mais...](https://github.com/aasouzaconsult/lakehouse))

-----------

# Case de Estudo - Visualização
- Censo Escolar 2020
  - Base de dados ([download](https://github.com/aasouzaconsult/business_intelligence/blob/main/Censo2020_inep.csv))
  - Power BI Desktop ([download](https://www.microsoft.com/pt-br/download/details.aspx?id=58494))
  - Arquivo do Power BI (.pbix) ([download](https://github.com/aasouzaconsult/business_intelligence/blob/main/PowerBI.pbix))
  - Link Público do case ([download](https://app.powerbi.com/view?r=eyJrIjoiOGVlMzVhMTEtMjdiZi00NjM3LThkOWQtYzRhYTBhZWIwYmYxIiwidCI6Ijc5YmY2Y2FlLWMwZWEtNGMzOS04ODgzLWVkNzIzY2Y1NTQ5MiJ9))

-----------

## Dashboards e Relatórios

Com base nos dados acima (DW), nos pediram para criarmos Dashboards e algumas análises, tais como Análises de Produtos, Clientes, Previsão de Vendas, e algo para Mobile, que serão detalhados a seguir.

### Dashboard de Vendas
- Quantidade e Valor total de Vendas (Cartões)
- Valor por Estado (Mapa)
- Correlação entre Quantidade e Total de Vendas
- Previsão de Vendas (por Ano)
- Valor de Vendas por Produto (Top 10)
- Top 10 Clientes (por Total de Vendas)
- Gráfico de colunas agrupadas e Linhas (quantidade e total de Vendas)
- Rentabilidade por canal de Venda 

### Dashboard Clientes
Já no que se diz respeito as análise de Clientes, a *sales.z* gostaria de entender melhor o comportamento deles, por exemplo:
- Quais compram mais
- Produtos comprados por Cliente
- Valor de Vendas por Cliente
- Mapa com informações sobre Clientes

### Dashboard Pessoal
Aqui, a *sales.z* precisará da relação de seus vendedores e seus respectivos dependentes
- Listagem de Vendedores (nome) e o Estado em que vende
- Listagem de Vendedores (nome) e seus respectivos Dependentes (nome e data nascimento)
- Dependentes e o nome da Escola que estuda (enriquecimento de dados - [dica](https://github.com/aasouzaconsult/banco-de-dados-para-analistas-e-cientistas-de-dados/blob/main/sales.z/Censo2020_inep.csv))

## Dicas e pontos avaliados pela **data.z consultoria**
- Criação de:
  - Métricas
  - Drill Down
  - Slices
  - Planos de fundo
  - Botões
  - Explorar recursos das ferramentas
  - Inove, crie e use sua criatividade
  - Storytelling
  - Mobile (celular)
  - Publique no Power BI Web
  
  -----------
**Alex Souza**
- [Portfólio de Serviços](https://github.com/aasouzaconsult/Cientista-de-Dados)
- [Blog](https://medium.com/blog-do-zouza)
- [Linkedin](https://www.linkedin.com/in/alex-souza/)
- [Instagram](https://www.instagram.com/alexsouzamsc/)


