# COM130 - Fundamentos de Internet e Web

Apresentar noções sobre a estrutura de documentos na Web:
- Hipertexto; 
- Origens de XML e HTML (SGML); 
- Estrutura do conteúdo versus aparência do documento; 
- Tags HTML básicas (H1, P etc.) e extensíveis (div, span etc.);
- Atributos básicos de CSS (color, text-align etc.), seletores CSS; 
- Javascript;
- Formulários HTML; Noções de manipulação programática do DOM. 

## Exercícios práticos:

Relacionei os exercícios realizados no 4º bimestre/2020 durante as aulas da disciplina COM130 do Curso de Bacharel de Ciência de Dados da Univesp. Abaixo segue uma breve descrição do problema de negócios e da solução (o link direciona para o código):

1. [Tabelas](tables.html): Implementar uma lista telefônica em uma estrutura em estrutura de tabela em HTML5;
2. [Marcadores HTML](Sem4_aula1.html): Criar uma página com as tags h1 .. h6, p, aside, dfn, svg, blockquote, listas, article, a, footer;
3. [Converter divs em HTML5](div_TO_html5/): dada uma página formatada com _div_ use as tags HTML5 que correspondam a estrutura adequada;
4. [Converter CSS das divs em HTML5](formato.css): dada uma página formatada com _div_ use as tags [HTML5](formato321.css) que correspondam a estrutura CSS adequada;
5. [Site de eletrônicos](https://github.com/wecchi/univesp_com130/tree/main/tv): criar uma estrutura HTML5 com CSS que contemple 2 páginas de navegação para apresentação de equipamento eletrônico;
6. [Layout com CSS - comercial](layout.html): estrtura de uma página web com _section_ contendo links externos na forma de menu _nav_, espaço para _ads_, _article_, _aside_ e _footer_.
7. [Layout com CSS - currículo](cv/): estrtura de uma página web com _section_ contendo tabelas para apresentação curricular de um aluno e formulário para contato.
8. [Resumo das TAGs HTML5](resumo_tags_html5.html):





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