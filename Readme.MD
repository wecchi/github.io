# Marketing Analytics

_Marketing Analytics_ é aplicar Data Science aos dados de todos os canais de marketing consolidando em uma visão comum:
- permite aos profissionais de Marketing avaliar o sucesso de suas iniciativas.
- isso é feito medindo o desempenho das campanhas de Marketing, coletando os dados e analisando os resultados.  O Marketing está surtindo efeitos? (Divulgar produtos ou serviços).
- utiliza métricas importantes de negócios, como ROI (Retorno Sobre o Investimento), Atribuição de Marketing e Eficácia Geral do Marketing.
- Estes são alguns exemplos de tipos de questões a serem abordadas analises de marketing:
	- Como estão as nossas iniciativas de marketing hoje? E a longo prazo? O que podemos fazer para melhorá-las?
    - Como nossas atividades de marketing se comparam às de nossos concorrentes? Onde eles estão gastando seu tempo e dinheiro? Eles estão usando canais que não estamos usando?
    - Nossos recursos de marketing estão alocados corretamente? Estamos dedicando tempo e dinheiro aos canais certos?
    - Como devemos priorizar nossos investimentos para o próximo ano?
    - Qual o perfil dos nossos clientes? Eles são da mesma área regional? Tem os mesmos gostos e preferências? Qual a faixa etária que mais consome o produto _A_?
    - Consigo segmentar meus clientes por similaridade? Tenho como saber os gastos por estes grupo?
    - De onde surgiu a venda (geograficamente ou pelo canal de vendas da internet)?
    - Quantas vezes o cliente visita a página antes de consumar uma compra? Existe melhoria na conversão dos clientes se mudarmos a cor das páginas?

## Projetos:

Abaixo segue uma breve descrição do problema de negócios e da solução de alguns projetos em Data Science (o link direciona para o código):

### 1. [Segmentação de clientes](SegmentacaoCliente.ipynb) para _Food Delivery_

#### Objetivo
O departamento de marketing da empresa _The Ninga_ requer um melhor conhecimento de seus clientes, para isso necessitam de uma segmentação baseada nos últimos 10.000 itens pedidos para traçar um planejamento e atender a estratégia de:
- Criar três campanhas de marketing para aumentar as vendas de pizza nos meses de Janeiro, Fevereiro, Junho e Julho.
- Implantar 4 campanhas, uma para cada um dos períodos (manhã, tarde, noite e madrugada) respectivamente a fim de maximizar a quantidade de itens por pedido como um todo.

#### Metodologia utilizada
Aplicação de modelo para clustorização (aprendizado não supervisionado) para reconhecer grupos de padrões nas variáveis solicitadas pela área de marketing e auxiliar nas estratégias das campanhas a serem criadas.

### 2. [Teste A/B](TesteAB.ipynb) para _e-commerce_

#### Objetivo
O departamento de marketing precisa descobrir se determinados produtos no site de vendas on-line são melhores promovidos **sem** apresentação das avaliações de clientes. Para isso foram criadas páginas sem avaliação dos clientes e coletadas informações quanto a conversão (venda):
- _Variante A_: A página exibe o número atual de comentários e as avaliações de usuários
- _Variante B_: A página não mostra os comentários de usuários no site

#### Metodologia utilizada
Aplicação de teste de hipótese para o seguinte cenário:
- $H_{0}: (P_{B} - P_{A}) = 0$
- $H_{1}: (P_{B} - P_{A}) > 0$

>$H_{0}$ nos diz que a diferença de probabilidade dos dois grupos é igual a zero.<br />
$H_{1}$ nos diz que a diferença de probabilidade dos dois grupos é maior do que zero.

### 3. [Indicadores de Performance](IndicadoresPerformance.ipynb)

#### Objetivo
Analistas  de  uma  empresa  que  comercializa  produtos  importados  dos  mais variados tipos para diversos países ao redor do mundo precisam analisar e interpretar 8 indicadores chave de performance com base nos dados fornecidos. Os  indicadores  foram  definidos  pela  área  de  planejamento  estratégico  da  empresa  que  precisa acompanhar a evolução das vendas e a efetividade das campanhas de Marketing ao longo do tempo:
1. Faturamento Mensal
2. Taxa (%) de crescimento mensal
3. Clientes ativos por Mês no Brasil
4. Total compras por mês no Brasil
5. Faturamento médio mensal por país
6. Diferença de faturamento ao longo do tempo entre clientes novos e antigos
7. Taxa de novos clientes
8. Taxa mensal de retenção de cliente

#### Metodologia utilizada
Tratamento dos dados fornecidos e criação dos indicadores para 12 meses.

### 4. [Mix de produtos](MixProdutos.ipynb)

#### Objetivo
A empresa *Lua Smart Techmonta* vende os modelos de smartphones, **Lua1**, **Lua2**, **Lua3**, **Lua4**, **Lua5**. A empresa está elaborando uma campanha *X* de marketing digital nas principais mídias sociais e precisa decidir quantas unidadesde de cada um dos modelos vai promover. Considerando que não há nenhum smartphone em estoque para esta campanha *X* e que após a camanha esses modelos serão atualizados e, por tanto, a empresa não quer manter nada em estoque.<br />
<mark> A *LuaSmart Tech* deseja saber quantas unidadesde de cada um de seus atuais modelos deve produzir (montar, testar e trabalhar na campanha de marketing *X*) para **maximizar seu lucro líquido**</mark> tendo como restrição não exceder mais horas de trabalho do que as disponíveis e também não deseja produzir mais do que pode vender pelos canais digitais; conforme seu plano de vendas elaborado pelo Departamento de Marketing:

|Modelo|Qtde máxima da<br> campanha ($N_i$)|Valor unitário <br> para venda ($V_i$)|
|:-----|--------------------------------:|-------------------------------------:|
|Lua1|500|640|
|Lua2|600|790|
|Lua3|750|880|
|Lua4|900|950|
|Lua5|1200|1100|

#### Metodologia utilizada
Para resolver problemas lineares como mix de produtos contendo regras e restrições, utilizarei a biblioteca _PuLP_.