Atividade para a disciplina de big data com o professor Marco Mialaret

A base de dados analisada é disponibilizada pela Agência Nacional do Petróleo, Gás natural e Biocombustíveis(ANP) e abrange os períodos de Maio 2004 à Maio de 2021.

A Agência divulga semanalmente relatórios sobre os preços do gás, diesel e outros combustíveis utilizados nos transportes em todo o país. Esses conjuntos de dados trazem o valor médio por litro, número de postos de gasolina analisados ​​e outras informações agrupadas por regiões e estados do Brasil.

A análise de variações nos preços dos combustíveis é importante devido ao impacto econômico significativo que ele causa no bolso dos consumidores brasileiros e que afeta custos de produção e o custo de transporte de bens e serviços, além disso, o constante aumento dos preços pode impulsionar uma crescente transição para fontes de energias sustentáveis e carros elétricos.

Os valores NULOS são representados na tabela pelo valor -99999

DICIONÁRIO DE VARIÁVEIS

-DATA INICIAL - Data de início da coleta de dados (Dtype - date)

-DATA FINAL - Data final da coleta de dados(neste dataset as datas inicial e final correspondem ao período de uma semana) (Dtype - datee)

-REGIÂO - Região brasileira onde foi feita a coleta de dados (Dtype - String)

-ESTADO - Estado brasileiro onde foi feito a coleta de dados (Dtype - String)

-PRODUTO - Tipo de combustível analisado (Dtype - String)

-NÚMERO DE POSTOS PESQUISADOS - Quantidade de postos pesquisados durante o período de coleta(uma semana) (Dtype - integer)

-UNIDADE DE MEDIDA - Unidade de medida utilizada para representar o combustível e método de venda (ex: R$/Litro) (Dtype - String)

-PREÇO MÉDIO REVENDA - Média do preço final cobrado ao consumidor nos postos de combustíveis (Dtype - double)

-DESVIO PADRÃO REVENDA - Calculo do grau de variação nos preços de revenda (Dtype - double)

-PREÇO MÍNIMO REVENDA - Menor preço encontrado nos postos de combustíveis durante o período pesquisado (Dtype - double)

-PREÇO MÁXIMO REVENDA - Maior preço encontrado nos postos de combustíveis durante o período pesquisado (Dtype - double)

-MARGEM MÉDIA REVENDA - Média da margem de lucro obtida na revenda durante o período pesquisado (Dtype - double)

-COEFICIENTE DE VARIAÇÃO REVENDA - Variabilidade do preço de distribuição em relação média observada (Dtype - double)

-PREÇO MÉDIO DISTRIBUIÇÃO - Média do preço de venda dos combustíveis para os postos (Dtype - double)

-DESVIO PADRÃO DISTRIBUIÇÃO - Calculo do grau de variação do preço pago pelos postos nas distribuidoras (Dtype - double)

-PREÇO MÍNIMO DE DISTRIBUIÇÃO - Preço mínimo pago pelos postos nos combustíveis (Dtype - double)

-PREÇO MÁXIMO DE DISTRIBUIÇÃO - Preço máximo pago pelos postos nos combustíveis (Dtype - double)

-COEFICIENTE DE VARIAÇÃO DISTRIBUIÇÃO - Variabilidade do preço de distribuição em relação média observada (Dtype - double)

