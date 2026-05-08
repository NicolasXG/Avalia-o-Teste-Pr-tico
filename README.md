Instruções de Execução

Este projeto realiza o tratamento e análise de dados ambientais utilizando Python, gerando tabelas formatadas em Excel e gráficos automáticos.

Funcionalidades
Leitura e tratamento de dados climáticos e ambientais;
Preenchimento de valores ausentes com média;
Conversão e organização de datas;
Cálculo de médias estatísticas;
Geração de gráficos em PNG;
Exportação dos resultados em arquivo Excel formatado;
Compactação dos resultados em arquivo .zip.

Foi utilizado o método de médias para os números que estão em falta pela justificativa da pouca discrepância
entre os dados fornecidos de mesma categoria, que por isso julguei ser o método mais coerente para situação.
Fiz a escolha do gráfico Temperatura X Nível do Rio para uma correlação lógica, a temperatura pode significar mudanças climáticas
que afetam diretamente o rio, como exemplo, um período de chuva que traz calor e aumenta o nível fluvial.
Fiz a escolha do gráfico NDVI x Nível do Rio para uma observação essencial para qualidade da água.

Bibliotecas Utilizadas
pip install pandas openpyxl numpy matplotlib

Como Executar
Abra o arquivo Avaliação.ipynb no Google Colab.
Execute todas as células em ordem.
Ao final da execução serão gerados os seguintes arquivos:
resultado.xlsx
grafico_temperatura.png
grafico_ndvi.png
grafico_linhas_duplas.png
grafico_temp_ndvi.png
grafico_ndvi_rio.png
resultado_final.zip
