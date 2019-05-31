# Dados_Detran_Acidentes

Trabalho da matéria Laboratório de Banco de Dados, usando Jupyter Notebook.

Foram usados os dados do DETRAN relativos aos acidentes nas estradas Federais no ano de 2017.

Foi usada uma tabela no formato CSV de onde foram filtradas as informações e extraídos os gráficos apresentados. 

Inicialmente é feita a conexão pelo Jupyter Notebook, que acessa o arquivo CSV e mostra o tamanho da tabela e os cabeçários das colunas.

Em seguida tiramos de nossa meta de busca algumas colunas que não seriam usadas, que permanecem no arquivo original.

Fizemos uma busca por cidade e filtramos os 10 maiores valores, que gera uma nova tabela mostrando as 10 cidades com maior quantidade de acidentes ocorridos naquele ano.Com estes mesmos dados podemos gerar um gráfico de barras que permite visualizar melhor a proporção dos valores encontrados.

Foi realizada uma filtragem por dia da semana, que gerou um gráfico mostrando que há uma diferença pequena com mais ocorrências nos finais de semana. Com a filtragem por classificação de acidentes, a base de dados mostra a quantidade de acidentes onde ocorreram mortes, com vítimas e sem vítimas. A partir da tabela por dia da semana gerada foram separados os dados de mortos, feridos e ilesos para um arquivo separado e feito um gráfico mostrando o percentual de mortos e feridos nos acidentes em relação ao valor total de pessoas envolvidas.

Com a filtragem por Causas de Acidentes, foi apresentado um gráfico com as 8 principais causas de acidentes, com o destaque para a falta de atenção, que aparece em primeiro, numa quantidade muito maior que as demais causas, em segundo lugar aparece o excesso de velocidade.

Devido às causas acima, observa-se nos gráficos apresentados a seguir que não há proporção maior de acidentes em condições meteorológicas adversas, como chuva, ou durante a noite, como poderia ser esperado.

No gráfico seguinte é mostrado que o número de acidentes ocorridos em estradas com pista simples é um pouco maior que o de outros tipos de pista, mas a diferença não é muito grande. Já os horários com maior quantidade de acidentes ocorrem com mais frequência no final da tarde e começo da noite. 

Quanto aos tipos de acidentes, a maior quantidade é de colisão traseira, seguida de saída da pista, ambos provavelmente ligados à falta de atenção.

Para finalizar, segue um gráfico com as estradas onde ocorreram mais acidentes, com destaque para a BR-101 e BR-116, ambas com cerca de 8.000 acidentes durante o ano, uma média de 20 acidentes por dia; mas que também são as estradas com maior extensão, atravessando vários estados.

Alunos: João Manoel Franco e André Luiz Rodrigues de Paulo
5º ADS - FATEC SJC
