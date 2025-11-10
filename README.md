# SERS---GS-2o-semestre
💡 Opção A – Análise de Dados: Eficiência Energética em Ambiente Empresarial
📘 Descrição da Solução

Esta solução simula e analisa o consumo energético de uma empresa, permitindo identificar padrões de uso, desperdícios e oportunidades de otimização.
O objetivo é demonstrar como a análise de dados pode contribuir para práticas sustentáveis no ambiente de trabalho, promovendo eficiência, economia e responsabilidade ambiental.

A aplicação gera dados simulados de consumo horário (em kWh) durante um período de 30 dias, com base em parâmetros como número de funcionários, área da empresa e potência média de operação.
Em seguida, realiza:

📊 Análises estatísticas (total, média, pico e fator de carga);

⚠️ Detecção de desperdício fora do horário comercial (8h às 18h);

📈 Visualizações gráficas de consumo horário e diário;

💬 Sugestões automáticas de melhorias para eficiência energética.

Essa abordagem pode ser aplicada no contexto empresarial para:

Apoiar a gestão energética inteligente;

Identificar horários de pico e desperdício;

Avaliar impactos de práticas sustentáveis no ambiente de trabalho.

⚙️ Tecnologias Utilizadas

Python 3.10+

Bibliotecas:

pandas → manipulação de dados

numpy → simulação numérica

matplotlib → geração de gráficos

🚀 Execução no Google Colab

Acesse o Google Colab
.

Crie um novo notebook e copie o código do arquivo app_analise_energetica_empresa_colab.py.

Certifique-se de que as bibliotecas estão instaladas (caso não, execute):

!pip install pandas numpy matplotlib


Execute todas as células.

O notebook exibirá:

Relatório textual com estatísticas e alertas;

Gráficos de consumo horário e diário;

Sugestões de eficiência energética.


📊 Interpretação dos Resultados
Métrica	                               Descrição
Consumo total (kWh)            	Soma total de energia consumida no período analisado.
Consumo médio horário          	Média de energia consumida por hora.
Pico de consumo                	Maior valor observado de consumo horário.
Fator de carga	                Relação entre consumo médio e pico (quanto mais próximo de 1, mais estável é o uso).
Consumo fora do expediente	    Indica o percentual de energia usada fora do horário de trabalho (8h–18h).

🔎 Exemplo de Interpretação

Desperdício acima de 20% → alto consumo fora do expediente → recomenda-se sensores de presença e desligamento automático.

Fator de carga < 0.5 → uso de energia irregular → redistribuir horários de operação.

Fator de carga > 0.7 → bom equilíbrio e eficiência no uso da energia.

🌱 Conclusão

Esta solução demonstra como a análise de dados pode apoiar decisões estratégicas para sustentabilidade no ambiente corporativo.
Mesmo com dados simulados, ela mostra o potencial de aplicar inteligência computacional e automação analítica para reduzir desperdícios e melhorar a eficiência energética — passos fundamentais para o futuro do trabalho sustentável.
