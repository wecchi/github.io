# COM120 - Algoritmos e Programação de Computadores II

Composição de programas com múltiplos arquivos de código fonte, uso de bibliotecas, APIs (WEB) e GUIs. Noções de programação orientada a objetos. Depuração de programas. Testes automatizados.
Conceito e uso de pilhas, filas, listas, árvores. Recursão. Algoritmos de Ordenação e Busca.
Noções de gerenciamento de memória e manipulação de listas. Módulos e noções de objetos, arquivos. Modularização (módulos, bibliotecas, interfaces). Uso de APIs básicas da WEB e manipulação de dados (JSON). Criação de interfaces gráficas simples. Controle de Versão (GIT). 

## Exercícios práticos:

Relacionei os exercícios realizados no 4º bimestre/2020 durante as aulas da disciplina COM120 do Curso de Bacharel de Ciência de Dados da Univesp. Abaixo segue uma breve descrição do problema de negócios e da solução em Python (o link direciona para o código):

<dl>
<dt> Gerenciamento de memória, arquivos e depuração de programas</dt>
<dd>

1. [Extrair palavras de aquivo 1](Semana1/Aula02_Arquivos.py): leitura de um arquivo texto, imprime as palavras encontradas e retorna a quantidade de palavras e o tamanho do arquivo lido.
2. [Contar ocorrências de palavra num arquivo](Semana1/ProblemaPratico_4_7.py): leitura de um arquivo texto para obter quantidade de ocorrências de uma palavra a ser localizada.
3. [Extrair palavras de aquivo 2](Semana1/ProblemaPratico_4_8.py): leitura de um arquivo texto para obter quantidade de palavras (desconsiderando símbolos de pontuação) e impressão da lista de palavras.
4. [Contar linhas contendo palavra específica](Semana1/ProblemaPratico_4_9.py): impressão das linhas de um arquivo que contenham pelo menos uma ocorrência de uma palavra a ser localizada.
5. [Trocar primeiro com último item de uma lista](Semana1/ProblemaPratico_3.14.py): função trocaPU(), que aceita uma lista como entrada e troca a posição entre o primeiro e último elementos da lista
6. [Desenhar do símbolo da olimpíada](Semana1/ProblemaPratico_3.15.py): função olimpíadas(t), que faz com que a tartaruga t desenhe os anéis olímpicos.
7. [MDC - Obter Máximo Divisor Comum](Semana1/Sem1_textobase_cap3_p76.py): algoritmo para calcular o máximo divisor comum entre dois números
8. [Calcular força exercida por um líquido](Semana1/Sem1_textobase_cap3_p81.py): função para calcular a força exercida na válvula de um reservatório cilíndrico contendo um líquido de peso específico conhecido.
9. [Extrair raízes de uma equação do 2º grau](Semana1/Sem1_textobase_cap3_p87.py): algoritmo para calcluar raízes de uma equação de segundo grau (Ax² + Bx + C).
10. [Gerar e ler arquivo texto](Semana1/Sem1_textoBase_ex7_1_p169.py): trechos de códigos para gravação e leitura de um arquivo texto
11. [Gerar um arquivo com entrada de números reais 1](Semana1/Sem1_textoBase_ex7_1a_p173.py): programa que permaneça em laço lendo e gravando números reais em um arquivo até que seja digitado 0.
12. [Ler e somar números de um arquivo 1](Semana1/Sem1_textoBase_ex7_2a_p174.py): programa que leia um arquivo texto contendo um número inteiro em cada linha, exiba na tela e faça a totalização dos valores lidos.
13. [Gerar um arquivo com entrada de números reais 2](Semana1/Sem1_textoBase_ex7_1b_p173.py): programa que permaneça em laço lendo números reais até que seja digitado 0, gravando todos os números num arquivo a partir da lista de números criada.
14. [Ler e somar números de um arquivo 2](Semana1/Sem1_textoBase_ex7_2b_p175.py): leitura de arquivo com totalização de valores – solução com iterador de arquivo.
15. [Calcular média de temperaturas](Semana1/Sem1_textobase_cap3_p96.py): média de N temperaturas fornecidas pelo usuário
16. [Imprimir lista de compras com totais](Semana1/Sem1_textoBase_ex7_3_p177.py): leitura de um arquivo texto que contém diversas linhas que representam uma lista de compras. Impressão da lista com totais.
17. [Gerar inventário de estoque](Semana1/Sem1_textoBase_ex7_4_p178.py): programa que leia um número inteiro N (10 < N < 10.000) e grave um arquivo com N linhas, simulando um inventário de estoque contendo código do produto, quantidade em estoque, valor unitário e ICMS a ser aplicado.
18. [Processar inventário de estoque](Semana1/Sem1_textoBase_ex7_5_p179.py): programa que leia o arquivo CSV criado anteriormente, calculando o valor total em mercadorias e o respectivo crédito de ICMS.
19. [Testar problemas de encoding](Semana1/Sem1_textoBase_ex7_6_p181.py): algoritmo para leitura e para gravação de arquivos textos usando codificação de caracteres conflitantes, mais detalhes na [W3C](https://www.w3.org/International/questions/qa-what-is-encoding).
20. [Obter números primos](Semana1/Sem1_textoBase_ep7_1_p182.py): programa que leia um número inteiro N e grave em um arquivo em disco todos os números primos existentes no intervalo fechado [2, N], um número em cada linha.
21. [Criar arquivo no N números aleatórios](Semana1/Sem1_textoBase_ep7_2_p182.py): gere o arquivo NUMEROS.TXT com 2000 números, um em cada linha, gerados com a função randint no intervalo fechado [1, 100.000].
22. [Ordenar números aleatórios](Semana1/Sem1_textoBase_ep7_3_p183.py): programa que leia o arquivo NUMEROS.TXT gerado no exercício anterior, colocando-os em uma lista. Ordene a lista utilizando o método Bubble Sort e grave os números ordenados no arquivo “ORDENADOS.TXT”.
23. [Correção de BUGs](Semana1/ProblemaPratico_4_10.py): explicação do que causa o erro de sintaxe em cada instrução listada.
</dd>
<dt>Programação orientada a objetos, prezando pela modularização e reutilização de código</dt>
<dd>

24. [Classes Point e Vector](Semana2/Sem2_videoaula_POO1.py): conceitos de Orientação a Objeto. Criação das classes _Point_ e _Vector_ com métodos up(), down(), left(), right(), distancia(), subscrição dos métodos para a A classe _Vector_ para aceitar a adição de vetor e operações de produto, além de representação de string canônica. (exercícios 8.12, 8.14 e problema prático 8.8)
25. [Classes Funcionario e Gerente](Semana2/Sem2_videoaula_POO2-Exercicio.py): trabalhando com herança.
</dd>
<dt>Funções recursivas que auxiliam na proposta de soluções para problemas complexos</dt>
<dd>

26. [Calclular sequência de Fibonacci e Fatorial](Semana3/Sem3_Recursao.py): conceitos de recursão para reselver Fatorial e Fibonacci.
27. [Comparar tempo entre recursão e iteração](Semana3/Sem3_Recursao_Iteracao.py): comparando os tempos entre iteração e recursão. Conceitos de Memoização para otimizar função recursiva.
28. [Estudo do capítulo 10 - Recursão](Semana3/Sem3-txtBase.py): analisador de vírus num sistema de arquivos; busca binária em lista (dividir para conquistar); análise experimental de tempo de execução; retornando um dicionário para representar a tabela de frequência de uma lista.
29. [Estudo da Seção 5.4 - Recursividade](Semana3/Sem3-txtBase2.py): funções variadas: verifica se número é primo; intersecção de duas listas; soma dos elementos de uma lista; busca binária em lista ordenada; verifica se número é par ou ímpar; retorna lista de N números primos; checa divisibilidade entre dois números; conversor de base decimal para binária; cálculo de dígito verificador; valida valor de entrada num intervalo definido; conversor de base decimal para diversas bases - até base 36; inverter sequência de caracteres; verifica palíndromo.
</dd>
<dt> Estruturas de dados utilizadas para representação, manipulação e armazenamento de dados? **pilhas, filas e árvores**</dt>
<dd>

30. [Pilha](Semana4/Sem4_videoaula_Pilha.py): criação de classe _pilha_ para entendimento dos métodos _push_, _pop_, _top_ e _empty_.
31. [Fila](Semana4/Sem4_videoaula_Fila.py): criação de classe _fila_ para entendimento dos métodos _inserir_, _remover_, _top_ e _empty_; implementação de classe _filaBanco_ para geração e atendimento das senhas normais e prioritárias.
32. [Dicionário](Semana4/Sem4_textoBase_Dictionary.py): funções para retornar o dia da semana dada sua abreviatura; contar frequência de palavras um texto; operações matemáticas de conjunto (união, interseção, diferença e diferença simétrica).
33. [Desafio: verificar os pares de abre/fecha parênteses/colchetes/chaves](Semana4/Sem4_Desafio.py): fazer o parsing de uma expressão aritmética, que faz uso de parênteses, colchetes e chaves, retornando erro na caso de faltar fechar um desses elementos.
34. [Estudo da Seção 6.2 - Operações com conjuntos](Semana4/Sem4_textoBase_cap6_Conjuntos.py): trabalhando com os métodos dos conjuntos e dos dicionários - _clear_, _copy_, _difference_, _discard_, *intersection_update*, _isdisjoint_, _issubset_, _issuperset_, _pop_, _remove_, *symmetric_difference*, *symmetric_difference_update*, _union_, etc...
35. [Árvore](Semana4/Sem4_videoaula_Tree.py): criação da classe _Node_ para entendimento dos métodos _insert_, _remove_, _findval_ e _get_. Inserção das folhas pelos métodos polonês, polonês inverso e ordem. Cálculo dos parâmetros da árvore: vértices, arestas, extremidades e altura.
</dd>
<dt>Ordenação e busca: explorando alguns algoritmos de ordenação clássicos da área, elencando suas vantagens e desvantagens</dt>
<dd>

36. [Busca](Semana5/Sem5_Busca.py): trabalhando com buscas lineares e binárias.
37. [Ordenação](Semana5/Sem5_Ordenacao.py): compondo algorítmos para ordenação de listas (arrays) por seleção, por inserção, _bubble sort_, _merge sort_, _quick sort_, _heap sort_ e _shell sort_.
</dd>
<dt>Processamento de elementos da Web: compreendendo tags HTML e JSON</dt>
<dd>

38. [JSON](Semana6/Sem6_html_json.py): lendo formatos JSON por meio da urllib.request que permite requisitar e receber recursos da Web.
39. [Webcrawler](Semana6/Sem6_webcrawler.ipynb): explorando padrões em páginas WEB aplicando conceitos HTMLParser e LinkParser.
</dd>
<dt>implementando programas com interfaces gráficas (GUI - Graphical User Interface)</dt>
<dd>

40. [GUI](Semana7/Sem7_UI.py): trabalhando com _Widgets_ e montando a interface.
</dd>
<dt>Testes automatizados e revisão dos principais conceitos</dt>
<dd>

41. [Teste unitário](Semana8/Sem8_Testes.py): conceitos de testes unitários utilizando _unittest_.
42. [Introdução a programação funcional](Semana8/Funcional.py): estudo de programação funcional: Estados e Dados imutáveis; função _lambda_; pacote _toolz_; utilizando funções _map()_, _reduce()_ e classe _operator_.
43. [Revisão](Semana8/Sem8_Revisao.py): notação em listas, funções recursivas, orientação a objeto, herança; pilhas, filas e árvores binárias e buscas "em ordem", "polonesa" e "polonesa inversa".
44. [Prova](Semana8/Sem9_Prova.py): questões da prova: Orientação a Objetos e GUI usando _tkinter_.
</dd>

</dl>











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