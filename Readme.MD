# COM120 - Algoritmos e Programação de Computadores II

Composição de programas com múltiplos arquivos de código fonte, uso de bibliotecas, APIs (WEB) e GUIs. Noções de programação orientada a objetos. Depuração de programas. Testes automatizados.
Conceito e uso de pilhas, filas, listas, árvores. Recursão. Algoritmos de Ordenação e Busca.
Noções de gerenciamento de memória e manipulação de listas. Módulos e noções de objetos, arquivos. Modularização (módulos, bibliotecas, interfaces). Uso de APIs básicas da WEB e manipulação de dados (JSON). Criação de interfaces gráficas simples. Controle de Versão (GIT). 

## Exercícios práticos:

Relacionei alguns exercícios realizados no 4º bimestre/2020 durante as aulas da disciplina COM120 do Curso de Bacharel de Ciência de Dados da Univesp. Abaixo segue uma breve descrição do problema de negócios e da solução em Python (o link direciona para o código):

1. [Consumo de gasolina](Sem2-ActiveCode_ex_2_10.py): calcula o consumo de gasolina de uma carro em quilômetros por litro
2. [Área de um retângulo](Sem2-ActiveCode_ex_2_9.py): calcula a área de um retângulo a partir das informações de altura e largura
3. [Juros compostos](Sem2-ActiveCode_ex_2_7.py): calcula o valor final de juro compostos a uma taxa de 8% a.a.
4. [Split de palavras](Sem2-ActiveCode_ex_2_5.py): armazena cada uma das palavras de uma frase numa variável e depois imprime-as
5. [Comprimento da hipotenusa](Sem2-ActiveCode_scratch_6_4.py): dado o comprimento de dois lados de um triângulo, calcula sua hipotenusa
6. [Verifica se o número é ímpar](Sem2-ActiveCode_ex_6_8.py): recebe como argumento um inteiro e retorna True se for ímpar
7. [Média harmônica amortizada](MediaHarmonicaAmortizada.py): calcula a média harmônica amortizada para os números 3.6, 8.9, 10 com fator 4 para amortização
8. [O triângulo é retângulo?](Sem2-ActiveCode_ex_6_11.py): dado o comprimento de três lados de um triângulo, determina se o triângulo é retângulo
9. [String do sistema-L](Sem2-ActiveCode_strings_lys2.py): desenho simétrico utilizando a biblioteca turtle
10. [Contar letras de uma frase](contar_letras.py): dada uma frase e uma letra a ser contatada, a função informa quantidade de ocorrênicas
11. [Matriz simétrica? E sua transposta?](Aula20_Lista_multidimensional.py): cada uma matriz, verifica se a mesma é simétrica. Calcular sua transposta com laço _for in_
12. [Contar palavras numa sentença](Sem7-ex4_2.py): supondo que a variável previsão tenha recebido a string 'It will be a sunny day today', conta ocorrência da palavra 'day'
13. [Soma de matrizes](Sem7-ex5_9.py): dada duas matrizes de mesma dimensão, calclular a soma de seus elementos numa nova matriz com laço _for in_
14. [Palavras com 4 caracteres](Sem6-ex3_5.py): dada um frase, retorna apenas as palavras com 4 caracteres com laço _for in_
15. [Sequência numéricas](Sem6-ex3_7.py): utilizando laço _for in_, exibir sequências numéricas específicas
16. [Desafio da semana 6](Sem6-Desafio.py): como você implementaria um programa que precisasse calcular a média de 1 milhão de valores? 
17. [Desafio da semana 7](Sem7-Desafio.py): armazenando dados de aluno e disciplina existentes em listas num banco SQLite
18. [Extração de vogais](Prova_3.py): Implemente uma função em Python que receba uma string como parâmetro e imprima as vogais


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