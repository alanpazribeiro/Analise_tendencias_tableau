# Analise_tendencias_tableau
Projeto 11 - Automatizando análise de tedências de vídeos do Youtube com Tableau para o departamento de marketing.

Panel completo: https://public.tableau.com/views/Sterling__Draper_Anlise_YT/HistricodeTendncias?:language=pt-BR&:display_count=n&:origin=viz_share_link

## Objetivo do Projeto
Objetivo dos negócios: analisar o histórico de vídeos de tendências no YouTube via Tableau.

### Bibliotecas Utilizadas
 - Pandas
 - Tableau

## Descrição dos Dados:

### Fontes de dados para o dashboard:
Os engenheiros de dados prometeram criar uma tabela agregada chamada trending_by_time. Segue sua estrutura:
  - record_id — chave primária
  - region — país / região geográfica
  - trending_date — data e hora
  - category_title — a categoria de vídeo
  - videos_count — o número de vídeos na seção de tendências

    
### Com que frequência o dashboard será usado: 
- pelo menos uma vez por dia

### Usuário do dashboard de destino:
- gerentes de planejamento de anúncios em vídeo

### Conteúdo de dados do dashboard:
   - Vídeos de tendências do passado, divididos por dia e categoria
   - Vídeos de tendências, divididos por países
   - Uma tabela de correspondência entre categorias e países

### Parâmetros segundo os quais os dados devem ser agrupados:
   - Data e hora da tendência
   - Categoria de vídeo
   - País

### Os dados:
   - Histórico de tendências — valores absolutos com divisão por dia (dois gráficos: números absolutos e proporção percentual)
   - Eventos, discriminados por países — valores relativos (% de eventos)
   - A correspondência entre as categorias e os países — valores absolutos (uma tabela)

### Importância:
- todos os gráficos são igualmente importantes

### A tabela fica armazenada no banco de dados do youtube , criado especialmente para suas necessidades

### Intervalo de atualização de dados:
- uma vez a cada 24 horas, à meia-noite UTC



