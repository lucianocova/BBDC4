# BBDC4
repositório referente a projeto de TCC referente a utilizacao de ML para análise de ações do BBDC4


PROJETO DE PESQUISA Aluno: Luciano Leite da Cova

TÍTULO DO PROJETO DE PESQUISA: Previsão do Preço Médio de Ação BBDC4 baseado em Técnicas de Machine Learning.

INTRODUÇÃO: Um postulado do bom investidor é o investidor não pagar mais por um ativo do que seu valor justo (DAMODARAN, 2012). Mas, como obter o preço justo de uma ação diante de um mercado cada vez mais volátil e inconstante e com diversas abordagens metodológicas para tal?
De um modo geral, há dois principais modelos de avaliação do preço de uma ação: uma baseada na avaliação intrínseca do ativo, baseando-se nos fluxos de caixa que se espera sejam gerados durante sua vida útil, e outro baseado em avaliação relativa, método que estima o valor de uma ação baseado nos preços de mercado de ativos semelhantes (DAMODARAN, 2012).
O presente trabalho objetiva o estudo da relação de variáveis fundamentalistas da ação do Banco Bradesco, obtidas por meio dos demonstrativos contábeis e divulgados pela instituição, juntamente com dados de preço de fechamento de tais ações e dados estatísticos, tais como o desvio padrão amostral, média e escore Z; por fim, utilizando-se do conceito do teorema do limite central, pretende-se obter uma distribuição normal de distribuição a partir da média e, por consequência, a construção de um intervalo de confiança para a avaliação do preço atual do ativo x preço esperado dentro do intervalo. Deste modo, espera-se estudar uma nova abordagem que une tanto dados comumente utilizado na análise intrínseca do ativo (dados de balanço e DRE) como dados comumente utilizados na análise relativa e técnica (preço). 
Pretende-se utilizar a média histórica dos períodos, calculada por meio do Teorema do Limite Central a partir dos preços de fechamento da ação BBDC4, como saída do modelo de machine Learning, cujas entradas serão alimentadas juntamente com dados fundamentalistas da ação. Para tanto, pretende-se dividir as amostras em dados de treino e teste dentro de cada período dos demonstrativos contábeis a serem analisados.
O período máximo de análise será limitado pelo período histórico máximo a ser obtido da base de dados.
A presente avaliação pretende propor uma nova abordagem na avaliação do preço de uma ação, sem se limitar apenas às variações de preços comuns à análise técnica, ou à obtenção do preço intrínseco de uma ação por meio de dados fundamentalistas ignorando o preço praticado pelo mercado. Acima disso, pretende-se realizar o estudo da relação de dados fundamentalistas e do preço de fechamento, este tipicamente ignorado pelo Valuation tradicional no cálculo do preço intrínseco da ação.
Pretende-se utilizar modelos de Machine Learning para a elaboração de modelo de previsão dos dados da média dos preços, em especial utilizando-se modelos de Redes Neurais. 
A escolha e limitação da ação do Banco Bradesco se deve a fatores como:
•	Limitação a um ativo alvo no estudo por conta de limitações de capacidade computacionais e de tempo na obtenção e tratamento da base de dados. 
•	Relevância e peso na composição do Ibovespa;
•	Por consequência, possuir volume e constância nos pregões da bolsa. 
•	Ser uma empresa brasileira, com grande relevância de mercado, privada e, por consequência, alheia às pressões de mercado sofridas por empresas públicas (a exemplo de Petrobrás e Banco do Brasil), o que certamente acrescentaria complexidade adicional ao modelo.


OBJETIVO: O objetivo do presente trabalho é, a partir das utilizações de técnicas de Machine Learning e análise estatística dos preços de fechamento da ação do Banco Bradesco e dados fundamentalistas da instituição, obter a previsão de dados estatísticos, em especial a média, do valor de cotação de um ativo para o próximo período, por consequência, seu valor.

MATERIAIS E MÉTODOS:  A base de dados a ser utilizada, foi extraída no site Fundamentus (para dados dos balanços/DRE), bem como as referências de preço de cotação de fechamento da ação BBDC4 pelo Yahoo Finance. Poderá haver mudança na fonte da base de dados se, ao longo do desenvolvimento da base de dados, for identificado melhor fonte, mudança ou indisponibilidade das fontes originalmente pensadas para tal finalidade, não prejudicando a elaboração do presente projeto, porém. 

RESULTADOS ESPERADOS: O presente Trabalho de Conclusão de Curso pretende obter um estudo de como a relação entre dados fundamentalistas juntamente com preço de fechamento de mercado podem ser variáveis relevantes na construição de um modelo de Machine Learning de previsão do preço de uma ação.

REFERÊNCIAS BIBLIOGRÁFICAS: 

Site Fundamentos. Disponível em: https://www.fundamentus.com.br/ Acesso em 15/10/2022.

Site Yahoo Finance. Disponível em: https://finance.yahoo.com/ Acesso em 15/10/2022.

DAMODARAN, Aswath. Valuation: Como Avaliar Empresas e Escolher as Melhores Ações. 1°. ed. Rio de Janeiro - RJ: LTC, 2012. 220 p. ISBN 8521620497.
