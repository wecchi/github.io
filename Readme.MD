# COM150 - Fundamentos matemáticos para computação

Conceitos de matemática discreta e de lógica para computação (lógica formal e lógica de predicados). Noção de complexidade. Técnicas de demonstração direta, demonstração por contraposição e demonstração por absurdo. Relaçaõ de recorrência, provas, indução matemática.
Uso da lógica formal em programação declarativa e na demonstração de correção de um algoritmo.
Relações e conceitos de teoria de grafos. Modelagem de problemas usando grafos. 

## Exercícios práticos:

Relacionei os exercícios realizados no 4º bimestre/2020 durante as aulas da disciplina COM150 do Curso de Bacharel de Ciência de Dados da Univesp. Abaixo segue uma breve descrição do problema de negócios e da solução em Python (o link direciona para o código):

1. [Relação de recorrência 1](Sem4_Recorrencia.py): Judith L Gersting (Seção 3.1). Exercícios diversos para estabelecer definições e obter soluções para relações recorrentes com uso de algoritmos recursivos.
2. [Relação de recorrência 2](Sem4_formula_fechada_2_ordem): Judith L Gersting (Seção 3.2). Criando uma seguência com 4 casos básicos. Fórmula fechada de segunda ordem.
3. [Relação binária com matrizes](Sem5_Matriz.py): criação da classe Matrix e implementação de operadores lógicos e aritméticos, diagonal principal e secundária, características (ordem, identidade, triangular superior, triangular inferior). Cálculo da matriz de acessibilidade para grafos a partir da matriz boolena  de adjacência.
4. [Conversor polonês ou "pré-ordem"](Sem6_infix_to_postfix.py): dada uma equação algébrica "em ordem" transformá-la em ordem polonesa ou "pré-ordem".
5. [Conversor polonês inverso ou "pós-ordem"](Sem6_toRpn.py): dada uma equação algébrica "em ordem" transformá-la em ordem polonesa inversa ou "pós-ordem".
6. [Conversor de expressão](Sem6_preprocessExpression.py): conversor gráfico de expressão para operadores booleandos entre "pré-ordem" e "pós-ordem" - infixToPostfix.
7. [Circuitos e caminhos em grafos](Sem7_Circuitos_e_caminhos.py): obter a mínima distância entre a origem e destino em um grafo direcionado com pesos em seus vértices.  
8. [Algoritmo de Dijkstra](Sem7_Dijkstra.py): obter o menor caminho entre dois vértices ponderados de um grafo, usando o algoritmo de Dijkstra.
9. [Caminho Hamiltonioano](Sem7_Hamiltoniano.py): obter todos os possíveis caminhos Hamiltonianos para um grafo a partir de um determinado vértice. Checar se existe um ciclo. Num caminho Hamiltoniano todos os vértices de um grafo devem ser visitados apenas uma única vez.
10. [Caminho de Euler](Sem7_Euler.py): verificar se um grafo possui um caminho de Euler. Obter o caminho de Euler. Num caminho de Euler todas as arestas de um grafo devem ser visitados apenas uma única vez.
11. [Algoritmo de Warshall](Sem7_Warshall.py): dado um grafo _G_ com _n_ nós, o algoritmo de _Warshall_ deve calcular uma sequência de _n + 1_ matrizes de acessibilidades M<sub>0</sub>, M<sub>1</sub>, M<sub>2</sub>, …, M<sub>n</sub>.


# Social Analytics

Como mensurar a consequência de campanhas nas redes sociais? Marketing digital, ou internet marketing, é o poder de mensuração de campanhas e observação de ROI (retorno sobre o investimento), além de saber a origem e a quantidade da audiência proveniente da internet, propriedade e experiência de navegação em websites, sites institucionais, portais de notícias e lojas virtuais. Assim como é possível determinar a quantidade de formação de leads e conversões (pedidos de orçamento, download de aplicativos, assinatura de newsletter, venda de produtos,..), rentabilidade e lucro.

## Social Data Mining:
- mineração de dados das mídias sociais
- análise de dados sistemática das informações geradas nas mídias sociais
- requer a tecnologia adequada para tratar Big Data (estima-se que apenas 20% dos dados são relevantes, os demais são ruídos)
- quanto "alguém" está realmente influenciando outros na WEB?
- planejamento pró-ativo, em tempo real
- pode auxiliar a detectar possíveis clientes
- influencia a forma de aprendizado e entendimento de assuntos relacionados a um produto/serviço
- permite compartilhar opiniões em tempo real, por exemplo, ao experimentar um produto e/ou serviço no momento em que a compra ocorre
- O que faz das mídias sociais um lugar tão interessante para a uma marca de um produto ou serviço? O público está lá.
	- Produção de conteúdo
	- Monitoramento de campanhas
	- Engajamento
	- Atendimento
	- Análise de sentimento

## Projetos:
Abaixo segue uma breve descrição do problema de negócios e da solução de alguns projetos em Data Science (o link direciona para o código):


### 1. [Palavras relacionadas](SocialNetworkAnalytics-Twitter.R) ao tema central _COVID_

#### Objetivo
O departamento de marketing da empresa _ABCD_ quer elaborar uma campanha de marketing e para isso busca palavras relacionadas e que estejam em evidência no Twitter a fim de potencializar a campanha.

#### Metodologia utilizada
Coleta, extração e limpeza do texto, criação de Corpus e da matriz de termos, análise junto com a área solicitante  a fim de ajustar os pesos das palavras, criação de nuvem de palavras

<div align="center">
       <img width="90%" src="COVID_CNN_Twitter.JPG" alt='nuvem de palavras'>
</div>

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