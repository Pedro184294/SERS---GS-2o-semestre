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

O relatório apresenta diversas métricas que ajudam a entender o comportamento energético da empresa:

Consumo total (kWh): representa a soma de toda a energia utilizada no período analisado.
Esse valor indica o tamanho do consumo global da empresa e serve de base para comparações futuras, após a adoção de medidas de eficiência.

Consumo médio horário: é a média de energia consumida por hora durante o período.
Essa métrica mostra a intensidade média de uso de energia e ajuda a perceber se há variações significativas ao longo do dia.

Pico de consumo: mostra o maior valor de consumo horário registrado.
Valores de pico muito altos indicam sobrecarga ou horários de concentração de uso de equipamentos, o que pode aumentar custos e reduzir a vida útil da rede elétrica interna.

Fator de carga: é a relação entre o consumo médio e o pico de consumo.
Quanto mais próximo de 1, mais equilibrado e estável é o uso de energia.
Fatores de carga muito baixos (menores que 0,5) indicam grande variação de consumo, o que representa oportunidades de otimização operacional.


Consumo fora do expediente: indica o percentual de energia usado fora do horário de trabalho (8h às 18h).
Valores elevados nessa métrica sugerem desperdício, possivelmente devido a equipamentos deixados ligados, iluminação desnecessária ou sistemas de ar-condicionado em funcionamento sem necessidade.

🔎 Exemplo de Interpretação

Desperdício acima de 20% → alto consumo fora do expediente → recomenda-se sensores de presença e desligamento automático.

Fator de carga < 0.5 → uso de energia irregular → redistribuir horários de operação.

Fator de carga > 0.7 → bom equilíbrio e eficiência no uso da energia.

🌱 Conclusão

Esta solução demonstra como a análise de dados pode apoiar decisões estratégicas para sustentabilidade no ambiente corporativo.
Mesmo com dados simulados, ela mostra o potencial de aplicar inteligência computacional e automação analítica para reduzir desperdícios e melhorar a eficiência energética — passos fundamentais para o futuro do trabalho sustentável.
