# Analise-Impacto-Operacional-TI
Dashboard interativo e diagnóstico de dados focado em identificar gargalos operacionais nos chamados de alteração de horário para medir SLA e aumentar a conformidade nos chamados de TI/DP.

# 📊 Otimização de SLA em Chamados de TI
🏢 Cenário e Problema de Negócio
Solicitações de alteração de horários eram abertas em formato de texto livre e com informações incompletas. Isso gerava um intenso gargalo de comunicação (vai e volta de e-mails), resultando em atrasos de dias no SLA da TI e desperdício de horas úteis.

🛠️ Arquitetura e Ferramentas
Excel: Tratamento inicial e exploração de logs não estruturados.

Power BI: Modelagem de dados e construção do dashboard interativo.

DAX: Criação de medidas personalizadas (ex: cálculo de SLA e variações).

🔄 Processo de Análise (ETL)
Realizei a extração da base histórica de tickets e apliquei uma amostragem qualitativa, transformando textos livres e despadronizados em categorias de problemas quantificáveis. Após a limpeza, os dados foram carregados e modelados no Power BI.

💡 Resultados e Solução Proposta
A Causa: Identificou-se que o alto volume de erros e quebras de SLA era causado pela omissão de dados essenciais na abertura do chamado.

Mapeamento: O painel revelou quais setores mais erravam, permitindo direcionar treinamentos.

Ação de Negócio (Impacto): Propus a implementação de formulários estruturados (campos obrigatórios) para blindar o sistema na entrada. A projeção é zerar o gargalo inicial de comunicação, devolvendo horas úteis à equipe de TI e reduzindo custos operacionais.
