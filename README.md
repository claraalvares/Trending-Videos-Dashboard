# Dashboard - Análise de Vídeos em Alta no YouTube

## Sobre o Projeto

Este projeto tem como objetivo criar um dashboard automatizado para analisar vídeos históricos que entraram na seção de tendências do YouTube. O dashboard foi projetado para ajudar gerentes de marketing e planejadores de anúncios a acompanhar as tendências de vídeos por categoria, região e data. O objetivo é automatizar o processo de responder perguntas frequentes sobre as tendências dos vídeos e fornecer insights valiosos sobre a distribuição e popularidade das categorias de vídeos entre as regiões, com foco especial nos Estados Unidos.

## Objetivo de Negócio

- **Analisar vídeos históricos que estiveram em alta no YouTube** por categoria, região e data.
- **Automatizar a visualização de dados** para ajudar os gerentes a entender as tendências e tomar decisões baseadas em dados para campanhas de marketing.

## Principais Funcionalidades

- **Vídeos em Alta por Data e Categoria**: Visualize como as tendências dos vídeos mudam ao longo do tempo e por categoria.
- **Distribuição Regional**: Acompanhe como os vídeos em alta estão distribuídos entre várias regiões.
- **Correspondência entre Categorias e Países**: Analise a relação entre categorias de vídeos e regiões.
- **Filtros**: Filtros de data e região que modificam todas as visualizações do dashboard.

## Público-alvo

- **Usuários Principais**: Planejadores de anúncios em vídeo e gerentes de marketing da agência Sterling & Draper.
- **Frequência de Uso**: Diariamente, pelo menos uma vez por dia.

## Visão Geral dos Dados

Os dados para este projeto são provenientes de uma tabela chamada `trending_by_time`, criada pela equipe de engenharia de dados. A estrutura da tabela é a seguinte:

- **record_id**: Chave primária.
- **region**: País/região geográfica.
- **trending_date**: Data e hora em que o vídeo entrou em alta.
- **category_title**: Categoria do vídeo (por exemplo, Entretenimento, Música, Notícias, Política).
- **videos_count**: Número de vídeos em alta nesse dia, categoria e região.

Os dados são atualizados uma vez a cada 24 horas, à meia-noite UTC, e são armazenados no banco de dados do YouTube, criado especificamente para este projeto.

## Funcionalidades do Dashboard

### Visualizações

- **Histórico de Tendências**: Dois gráficos mostrando as tendências históricas:
  - **Contagem Absoluta de Vídeos**: Exibe o número total de vídeos em alta ao longo do tempo.
  - **Distribuição Percentual**: Exibe a proporção de vídeos por categoria ao longo do tempo.
  
- **Distribuição Regional**: Uma análise das tendências de vídeos por região, mostrando a porcentagem relativa de eventos entre os diferentes países.

- **Correspondência entre Categorias e Países**: Uma tabela que faz a correspondência entre as categorias de vídeos e os países, mostrando o número absoluto de vídeos em alta.

### Filtros

- **Filtro de Data e Hora**: Modifica todos os gráficos para exibir dados no intervalo de tempo selecionado.
- **Filtro de Região**: Modifica todos os gráficos para exibir dados na região selecionada.

### Ferramentas Utilizadas

- **Tableau Public**: Para criação e publicação do dashboard.

### Como Executar o Projeto  
1. Clone o repositório;  
2. Navegue até o diretório do projeto;  
3. Abra o arquivo no Tableau;  
4. Interaja e edite o dashboard.

## Licença

Este projeto está licenciado sob a Licença MIT - consulte o arquivo [LICENSE](LICENSE) para mais detalhes.


-------------------

# Dashboard - YouTube Trending Videos Analysis

## About the Project

This project aims to create an automated dashboard to analyze historical videos that appeared in the YouTube trending section. The dashboard is designed to help marketing managers and ad planners track video trends by category, region, and date. The goal is to automate the process of answering frequently asked questions about video trends and provide valuable insights into the distribution and popularity of video categories across regions, with a special focus on the United States.

## Business Objective

- **Analyze historical videos that trended on YouTube** by category, region, and date.
- **Automate data visualization** to help managers understand trends and make data-driven decisions for marketing campaigns.

## Key Features

- **Trending Videos by Date and Category**: Visualize how video trends change over time and by category.
- **Regional Distribution**: Track how trending videos are distributed across various regions.
- **Category and Country Match**: Analyze the relationship between video categories and regions.
- **Filters**: Date and region filters that modify all dashboard views.

## Target Audience

- **Primary Users**: Video ad planners and marketing managers at Sterling & Draper agency.
- **Frequency of Use**: Daily, at least once a day.

## Data Overview

The data for this project comes from a table called `trending_by_time`, created by the data engineering team. The structure of the table is as follows:

- **record_id**: Primary key.
- **region**: Country/Geographic region.
- **trending_date**: Date and time when the video trended.
- **category_title**: Video category (e.g., Entertainment, Music, News, Politics).
- **videos_count**: Number of trending videos on that day, category, and region.

The data is updated once every 24 hours at midnight UTC and is stored in a YouTube database specifically created for this project.

## Dashboard Features

### Visualizations

- **Trending History**: Two charts showing historical trends:
  - **Absolute Video Count**: Displays the total number of trending videos over time.
  - **Percentage Distribution**: Displays the proportion of videos by category over time.
  
- **Regional Distribution**: An analysis of video trends by region, showing the relative percentage of events across different countries.

- **Category and Country Match**: A table that maps video categories to countries, showing the absolute number of trending videos.

### Filters

- **Date and Time Filter**: Modifies all charts to display data for the selected time period.
- **Region Filter**: Modifies all charts to display data for the selected region.

### Tools Used

- **Tableau Public**: For creating and publishing the dashboard.

### How to Run the Project  
1. Clone the repository;  
2. Navigate to the project directory;  
3. Open the file in Tableau;  
4. Interact with and edit the dashboard.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

