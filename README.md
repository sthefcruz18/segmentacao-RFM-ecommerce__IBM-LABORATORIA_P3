# Projeto 3 - Segmentação de clientes de e-commerce através do método RFM<br>

## Competências e Habilidades desenvolvidas:<br>
🎯 **Pré-processar dados em planilhas:** identificar dados duplicados, em branco ou fora do domínio (por exemplo, valores negativos quando não aplicável) para preparar seus dados para análise posterior.

🎯 **Organizar dados em planilhas:** conhecer os diferentes tipos de dados que uma célula aceita e conseguir formatar moedas, datas, números para melhor visualizar as informações. Além disso, usar filtros para organizar os dados e poder ordenar as colunas do maior para o menor (ou vice-versa) de acordo com o tipo de dados.

🎯 **Manipular dados em planilhas:** usar tabelas dinâmicas para calcular, resumir e analisar dados para ver comparações, padrões e tendências neles. Além disso, poder conectar duas ou mais fontes de dados usando a função PROCV (VLOOKUP).

🎯 **Visualizar dados em planilhas:** Fazer gráficos de linhas e barras para visualizar informações, resumir descobertas, encontrar padrões ou comparar diferentes séries de dados.

🎯 **Fazer uma análise de coorte:** organizar as informações para formar coortes de clientes de acordo com a data de entrada no produto/serviço. Realizar cálculos e formatar as informações para encontrar mapas de calor. Identificar pontos de fuga.

🎯 **Segmentar clientes utilizando o modelo RFM:** entender a regra de Pareto e utilizá-la para identificar os principais clientes do negócio, a fim de concentrar esforços e obter o maior retorno (80/20).

## Ferramentas utilizadas: <br>
<img src="https://img.shields.io/badge/-Sheets-brightgreen"/>   <img src="https://img.shields.io/badge/-Data%20Studio-blue"/>

## Relatório de Análise: <br>
📈 <a href="https://docs.google.com/spreadsheets/d/1w7iw3gIwWzWk0cDoxhZVXqjppch0bbDmSS5EyG64NWI/edit?usp=sharing">Relatório no Sheets</a> 

## Vìdeo de Apresentação dos Resultados: <br>
📹 <a href="https://www.loom.com/share/0b5376fec06648d5be8c0ed8dc095d97">Vídeo</a> 

## Dashboard interativo: <br>
🖼️ <a href="https://datastudio.google.com/reporting/584de949-be22-46b1-8d30-7dade399cd37">Data Studio Report</a>

## Objetivo da Análise: <br>
🎯 Realizar análise descritiva que mostrará à CEO de uma empresa de varejo o quão bem ou mal as vendas estão indo na empresa, medir o engajamento do cliente com base em uma análise de coorte e realizar uma segmentação de clientes aplicando a metodologia RFM, para que o negócio possa focar seus esforços e adotar estratégias diferenciadas para cada segmento.

## Etapas: <br>
1️⃣ **Importar, entender o conjunto de dados e limpar os dados:** Detecção de nulos ou vazios, Detecção e remoção de dados duplicados, Detecção e eliminação de quantidades negativas | funçãões: COUNTBLANK() e Remover cópias

2️⃣ **Análise das métricas de vendas:** Análise do número de faturas por país, Análise de valor total por país, Faturas geradas por mês, Número de faturas do Reino Unido versus estrangeiras por mês, Número de novos clientes por mês, Adicição de outros indicadores e Ordenação das informações | Tabelas dinâmicas e Gráficos, Funções  TEXTO(), IF(), COUNTUNIQUE() e COUNTA()

3️⃣ **Análise de coorte:** Replicar os dados em outra aba e criar a coluna coorte, Criar tabela dinâmica, Transformar tabela dinâmica em análise por mês | Tabelas dinâmicas e Gráficos, Funções QUERY e PROCV

4️⃣ **Segmentação de clientes através da metodologia RFM ou RFV:** Preparar um novo conjunto de dados, Cálculo de quartis para cada variável, Calcular o número de dias que passaram desde a última compra do cliente até o dia da análise (Recência), Calcular o número de faturas que estão associadas a cada cliente (Frequência), Calcular o valor total gasto pelo cliente (Monetário ou Valor), Criar diferentes codificações com caracterizações dos clientes, Analisar as informações considerando a Lei de Pareto (80/20) | Funções QUERY, DIAS(), QUARTIL(), IFS()

5️⃣ **Apresentação das conclusões:** Criação de Dashboard interativo no Google Data Studio


## Entregas e Conclusões: <br>
📝**Pré-processamento e Limpeza:** <br>
<img src="https://github.com/sthefcruz18/segmentacao-RFM-ecommerce__IBM-LABORATORIA_P3/blob/c3eb647ee7515a227702e1d1371ea5adf4c8d679/0.1_dataset_bruto.png"/><br>

<img src="https://github.com/sthefcruz18/segmentacao-RFM-ecommerce__IBM-LABORATORIA_P3/blob/c3eb647ee7515a227702e1d1371ea5adf4c8d679/0.2_limpeza_dataset.png"/><br>

<img src="https://github.com/sthefcruz18/segmentacao-RFM-ecommerce__IBM-LABORATORIA_P3/blob/c3eb647ee7515a227702e1d1371ea5adf4c8d679/0.3_dataset_limpo.png"/><br>


📝**Principais métricas de negócios**
<br><img src="https://github.com/sthefcruz18/segmentacao-RFM-ecommerce__IBM-LABORATORIA_P3/blob/c3eb647ee7515a227702e1d1371ea5adf4c8d679/1.faturas_por_pa%C3%ADs.png"/><br>

<br><img src="https://github.com/sthefcruz18/segmentacao-RFM-ecommerce__IBM-LABORATORIA_P3/blob/c3eb647ee7515a227702e1d1371ea5adf4c8d679/2.faturas_mes_origem.png"/><br>

<br><img src="https://github.com/sthefcruz18/segmentacao-RFM-ecommerce__IBM-LABORATORIA_P3/blob/c3eb647ee7515a227702e1d1371ea5adf4c8d679/2.faturas_mes_origem_2.png"/><br>

<br><img src="https://github.com/sthefcruz18/segmentacao-RFM-ecommerce__IBM-LABORATORIA_P3/blob/c3eb647ee7515a227702e1d1371ea5adf4c8d679/3.montante_vendas_mes_origem_1.png"/><br>

<br><img src="https://github.com/sthefcruz18/segmentacao-RFM-ecommerce__IBM-LABORATORIA_P3/blob/c3eb647ee7515a227702e1d1371ea5adf4c8d679/4.montante_por_pa%C3%ADs.png"/><br>

<br><img src="https://github.com/sthefcruz18/segmentacao-RFM-ecommerce__IBM-LABORATORIA_P3/blob/c3eb647ee7515a227702e1d1371ea5adf4c8d679/5.montante_vs_faturas_1.png"/><br>

<br><img src="https://github.com/sthefcruz18/segmentacao-RFM-ecommerce__IBM-LABORATORIA_P3/blob/c3eb647ee7515a227702e1d1371ea5adf4c8d679/5.montante_vs_faturas_2.png"/><br>

<br><img src="https://github.com/sthefcruz18/segmentacao-RFM-ecommerce__IBM-LABORATORIA_P3/blob/c3eb647ee7515a227702e1d1371ea5adf4c8d679/5.montante_vs_faturas_3.png"/><br>

<br><img src="https://github.com/sthefcruz18/segmentacao-RFM-ecommerce__IBM-LABORATORIA_P3/blob/main/6.clientes_por_pa%C3%ADs.png"/><br>

<br><img src="https://github.com/sthefcruz18/segmentacao-RFM-ecommerce__IBM-LABORATORIA_P3/blob/main/7.clientes_unicos_mes_1.png"/><br>

<br><img src="https://github.com/sthefcruz18/segmentacao-RFM-ecommerce__IBM-LABORATORIA_P3/blob/main/7.clientes_unicos_mes_2.png"/><br>

<br><img src="https://github.com/sthefcruz18/segmentacao-RFM-ecommerce__IBM-LABORATORIA_P3/blob/main/8.top_10_clientes.png"/><br>

<br><img src="https://github.com/sthefcruz18/segmentacao-RFM-ecommerce__IBM-LABORATORIA_P3/blob/main/9.top_10_clientes_montante.png"/><br>

<br><img src="https://github.com/sthefcruz18/segmentacao-RFM-ecommerce__IBM-LABORATORIA_P3/blob/main/10.vendas_produtos_mes.png"/><br>

<br><img src="https://github.com/sthefcruz18/segmentacao-RFM-ecommerce__IBM-LABORATORIA_P3/blob/main/11.produtosXmontanteXfaturas_2.png"/><br>

<br><img src="https://github.com/sthefcruz18/segmentacao-RFM-ecommerce__IBM-LABORATORIA_P3/blob/main/11.produtosXmontanteXfaturas_2.png"/><br>

<br><img src="https://github.com/sthefcruz18/segmentacao-RFM-ecommerce__IBM-LABORATORIA_P3/blob/main/12.clientes_voltaram_comprar.png"/><br>


📝**Análise por coorte geral:**
<br>Com a tabela de coorte pelo mês da primeira compra, costruíu-se uma tabela da taxa de retenção com escala de cores, de modo a que pudessemos analisar visualmente a retenção dos clientes.

Ao analisar a taxa de retenção, conclui-se que o coorte com melhor retenção até o momento é o de clientes que fizeram a primeira compra em dezembro/2020.

Se considerarmos a taxa ideal de retenção para e-commerce em 30%, teremos apenas um coorte com retenção próxima do ideal, também dezembro/2020. Este coorte ficou dentro da retenção ideal durante todo o período analisado.

Ao visualizar a retenção num gráfico podemos verificar que a maioria dos coortes estão com porcentagem de retenção abaixo dos 30%.
Portanto a empresa ainda não atingiu a retenção ideal para uma empresa do ramo do e-commerce.

<br><img src="https://github.com/sthefcruz18/segmentacao-RFM-ecommerce__IBM-LABORATORIA_P3/blob/main/13.retencao_coorte_geral.png"/><br>
<br><img src="https://github.com/sthefcruz18/segmentacao-RFM-ecommerce__IBM-LABORATORIA_P3/blob/main/14.retencao_coorte_geral_grafico.png"/><br>


📝**Análise por coorte de clientes do Reino Unido:**
<br>Ao analisar a porcentagem de retenção apenas dos clientes do Reino Unido, verifica-se que o coorte com melhor retenção até o momento também foi o coorte de clientes que fizeram a primeira compra em dezembro/2020.

Este corte também foi o único a manter a retenção ideal durante todo o período analisado.

Cabe atenção aos coortes de janeiro e fevereiro/2021. Uma porcentagem significativa destes clientes voltaram a comprar nos últimos meses do período analisado.

Sugere-se uma ação para diagnosticar maiores informações sobre os clientes destes três coortes, a fim de identificar qual perfil de clientes do Reino Unido que a empresa conseguiu resgatar.

Outra tendência que podemos observar é que, mesmo não atingindo 30%, os meses finais do período analisado sempre há aumento de clientes que voltam a comprar. Reforçando que o final de ano contém os melhores meses para a empresa.

Ao visualizar a retenção num gráfico podemos verificar que a maioria dos coortes estão com porcentagem de retenção abaixo dos 30%.

Porém, visualiza-se também que nos meses finais do ano a tendência é que os clientes do Reino Unido voltem a comprar.

É interessante pesquisar quais estratégias estão sendo empregadas neste período, afim de replicá-las nos demais meses visando a retenção de pelo menos 30% dos clientes.	
		
<br><img src="https://github.com/sthefcruz18/segmentacao-RFM-ecommerce__IBM-LABORATORIA_P3/blob/main/15.retencao_coorte_UK.png"/><br>
<br><img src="https://github.com/sthefcruz18/segmentacao-RFM-ecommerce__IBM-LABORATORIA_P3/blob/main/16.retencao_coorte_UK_grafico.png"/><br>

📝**Análise por coorte de clientes FORA do Reino Unido:**
<br>Com a tabela de coorte pelo mês da primeira compra, costruíu-se uma tabela da taxa de retenção dos clientes estrangeiros numa escala de cores, de modo a que pudessemos analisar visualmente a retenção dos clientes, desta vez apenas dos estrangeiros.

Ao analisar a taxa de retenção conclui-se que o coorte com melhor retenção até o momento também foi o de clientes que fizeram a primeira compra em dezembro/2020.

Se considerarmos a taxa ideal de retenção para e-commerce em 30%, teremos também apenas um coorte com retenção próxima do ideal, dezembro/2020. Este coorte ficou dentro da retenção ideal durante todo o período analisado.

Ao visualizar a retenção num gráfico podemos verificar que a maioria dos coortes também estão com porcentagem de retenção abaixo dos 30%.

Cabe ressaltar que a taxa de retenção de clientes estrangeiros oscila mais do que a dos clientes do Reino Unido.		
		
<br><img src="https://github.com/sthefcruz18/segmentacao-RFM-ecommerce__IBM-LABORATORIA_P3/blob/main/17.retencao_coorte_foraUK.png"/><br>
<br><img src="https://github.com/sthefcruz18/segmentacao-RFM-ecommerce__IBM-LABORATORIA_P3/blob/main/18.retencao_coorte_foraUK_grafico.png"/><br>

📝**Segmentação usando a metodologia RFM / RFV:** 
<br>Preparar um novo conjunto de dados, Cálculo de quartis para cada variável, Calcular o número de dias que passaram desde a última compra do cliente até o dia da análise (Recência), Calcular o número de faturas que estão associadas a cada cliente (Frequência), Calcular o valor total gasto pelo cliente (Monetário ou Valor), Criar diferentes codificações com caracterizações dos clientes, Analisar as informações considerando a Lei de Pareto (80/20)

<br><img src="https://github.com/sthefcruz18/segmentacao-RFM-ecommerce__IBM-LABORATORIA_P3/blob/main/19.dataset_segmentacao.png"/><br>
<br><img src="https://github.com/sthefcruz18/segmentacao-RFM-ecommerce__IBM-LABORATORIA_P3/blob/main/20.segmentacao_categorias.png"/><br>
<br><img src="https://github.com/sthefcruz18/segmentacao-RFM-ecommerce__IBM-LABORATORIA_P3/blob/main/21.origem_bons_clientes.png"/><br>
<br><img src="https://github.com/sthefcruz18/segmentacao-RFM-ecommerce__IBM-LABORATORIA_P3/blob/main/22.montanteVSfaturas_bons_clientes.png"/><br>

📝**Dashboard interativo no Google Data Studio:**
<br> <a href="https://datastudio.google.com/reporting/584de949-be22-46b1-8d30-7dade399cd37">Clique aqui para acessar o dashboard no Google Data Studio</a><br>
<br><img src="https://github.com/sthefcruz18/segmentacao-RFM-ecommerce__IBM-LABORATORIA_P3/blob/main/23.dashboard.png"/><br>

## Dataset: <br>
💻 Os dados são públicos e fictícios<br>
💻 Podem ser escontrados <a href="https://www.kaggle.com/datasets/datacertlaboratoria/projeto-3-segmentao-de-clientes-no-ecommerce">clicando aqui</a>
