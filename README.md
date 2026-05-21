# 📊 Otimização de SLA em Chamados de TI
Cenário e Problema de Negócio: Solicitações de alteração de horários eram abertas em formato de texto livre e com informações incompletas. Isso gerava um intenso gargalo de comunicação (vai e volta de e-mails), resultando em atrasos de dias no SLA da TI e desperdício de horas úteis.

![Visão geral do DASHBOARD](https://github.com/user-attachments/assets/ade4fc6d-2e57-4101-a350-e42912427ff1)

# Ação de Negócio (Impacto) 
Propus a implementação de formulários estruturados (campos obrigatórios) para blindar o sistema na entrada. Como resultado foi zerar o gargalo inicial de comunicação, devolvendo horas úteis à equipe de TI e reduzindo custos operacionais.

# Processo de Análise (ETL)
Realizei a extração da base histórica de tickets e apliquei uma amostragem qualitativa, transformando textos livres e despadronizados em categorias de problemas quantificáveis. Após a limpeza, os dados foram carregados e modelados no Power BI.

# Mapeamento
O painel revelou quais setores mais erravam, permitindo direcionar treinamentos.

# Arquitetura e Ferramentas
Excel: Tratamento inicial e exploração de logs não estruturados.
Power BI: Modelagem de dados e construção do dashboard interativo.
DAX: Criação de medidas personalizadas (ex: cálculo de SLA e variações).



