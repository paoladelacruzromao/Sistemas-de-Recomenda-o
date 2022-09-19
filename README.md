# Sistemas-de-Recomendação

Para todos os negócios ligados a comércio eletrônico, é provável que os sistemas de recomendação sejam a ferramenta analítica mais importante já implementada. Embora não existam estimativas oficiais, muitas fontes estimam que, para as principais plataformas de comércio eletrônico, como a Amazon e a Netflix, os sistemas de recomendação podem ser responsáveis por até 10% a 35% da receita destas empresas. Esses são números consideráveis. Em um mundo com baixo crescimento, conseguir aumentar em 10% o seu faturamento, faz dos sistemas de recomendação algo que devemos olhar com mais atenção. Vamos compreender o que são esses sistemas.

Sempre que falamos em alguma tecnologia que pode trazer benefícios financeiros para a empresa, que sejam significativos, os investimentos nesta tecnologia se justificam. E aí vemos uma  vantagem  dos  sistemas  de  recomendação  (ou  talvez  mais  uma).  O  custo  de implementação  desses  sistemas  é  relativamente  baixo  e  seus  ganhos  são  consideráveis. Sistemas de recomendação são apenas uma das muitas especialidades em rápida evolução dentro de análise preditiva e trabalho garantido para os Cientistas de Dados.

### O Que São Sistemas de Recomendação? ###

São as aplicações que personalizam a experiência de compra do cliente, recomendando as melhores opções seguintes à luz das suas recentes compras ou atividade de navegação.Sistemas de Recomendação são, portanto, modelos preditivos que a partir de análise estatística, determinam a probabilidade de um cliente estar interessado por um outro item similar ao que está comprando em um dado momento.

Sistemas de recomendação são simples, pelo menos, em seu objetivo. Mas é importante deixar claro, que enquanto sistemas de recomendação são usados em aplicativos de comércio eletrônico onde o cliente está comprando algo, eles são igualmente aplicáveis em situações em que você está tentando maximizar o tempo do usuário em umsite com a finalidade de aumentar a exposição publicitária. Um bom exemploé o portal do Yahoo que personaliza seu feed de notícias de modo que você gaste mais tempo no site. Este é um bom exemplo de aplicação de sistemas de recomendação. 

Você não sabe (ou pelo menos não sabia até agora), mas as notícias que vão sendo recomendadas a vocêno portal têmcomo objetivo aumentar sua exposição aos anunciantes do site, que pagam exatamente pelo número de  visualizações  ou  de  cliques  em  seus  banners.  Outros  exemplos  de  sistemas  de recomendação incluem associações e Market Basket Analysis que são tão úteis para atividades de Marketing.

### Tipos de Sistemas de Recomendação

Sistemas de recomendação não são todos iguais. Se você for implementar um sistema de recomendação pela primeira vez é muito provável que você comece com uma solução pronta de um fornecedor ou que vocêdesenvolva seu próprio sistema do zero usando R ou Python por exemplo e faremos isso daqui a pouco. Além das questões táticas de negócios sobre as considerações que devem ser feitas na implementação de sistemas de recomendação, é importante  conhecer  tecnicamente  o  que  são  esses  sistemas.  Isso  significa  olhar profundamente para  osdiferentes  tipos  de  sistema  de  recomendação  e  compreender  os pontos fortes e fracos de cada um.

Os tipos de sistemas de recomendaçãodependem de diferentes algoritmos.

•Alguns têm um foco maior nas semelhanças de clientes, alguns em similaridades de conteúdo e alguns uma mistura dos dois.

•Diferentes algoritmos variam em sua utilidade com base no quanto você sabe com antecedência sobre osclientes, seu conteúdo e se você pode obter feedback dos clientes após a compra (isso seria fundamental).

•Todos devem satisfazer a exigência geral de oferecer um resultado personalizado dentro de cerca de 50 milissegundos (esse é um desafio).

Os  sistemas  de  recomendação  se  resumem  a  oferecer  pontuações  aos  clientes  de acordo com vários critérios. Essas tags de pontuação que você coloca nos clientes eregistros de conteúdo raramente são em tempo real e são normalmente atualizadas durante a noite, mais ou menos frequentemente, dependendo decada circunstânciae objetivo de negócio. Portanto, as atualizações de pontuação off-line podem depender de cálculos recomendados, mas podem ser complementadas com pontuação e análise realizadas separadamente em uma escala de tempo mais longa. Ou seja, o que parece tempo real é na verdade quase tempo real.

Os avanços nos sistemas de recomendação não foram tão grandes quanto algumas outras áreas da ciência de dados. A mais complexa dessas opções, os Filtros Colaborativos,existem a mais dedez anos. De uma perspectiva empresarial a boa notícia é que você pode se sentir confortável construindo um portfólio de tecnologia existente e bem estabelecida. A maioria dos avanços na ciência dos dados em torno de sistemas de recomendação tem sido focada em melhorar gradualmente o seu desempenho nos domínios específicos em que foram implantados. E com a grande quantidade de dados disponíveis(Big Data), desempenho deve ser uma preocupação constante.Vamos estudar em mais detalhes cada um dos 5 tipos de sistemas de recomendação mostrados na figuraacima.

### 1. Sistema de RecomendaçãoBaseado no Item Mais Popular

Este é o modelo mais simples e básico de sistema de recomendação.A estratégia é simplesmente oferecer ao cliente o que é mais popular, seja um filme, um livro ou um artigo de vestuário. Sem fazer nada mais do que observar nosregistros de vendas, é possível  construir  um  sistema  de  recomendação  simples  como  esse.  

Isso  não  é necessariamente ciência de dados. Não é particularmente personalizado.Mas pode ser útil se você sabe muito pouco sobre o seu visitante. Exige alguns atributos de conteúdos que podem ser usados para criar subcategorias que podem corresponder à navegação atual do visitante em um site de comércio eletrônico.

Por exemplo, se você está oferecendo uma grande variedade de produtos como um único pacote ou combo,desde ferramentas a roupas, ou filmes, livros ou notícias que apelam para interesses diferentes,  então  você  precisará  tentar  combinar  itens  pelo  menos  na  mesma  categoria visualizada pelo seu visitante. Empresas como a rede de lojas Home Depot usa regularmente um espaço em seu website chamado de "best sellers" e a GAP usa regularmente "produtos mais recentes" para indicar os produtos mais populares, indicá-los a outros consumidores e aumentar  a  receita.  Esse  tipo  de  sistema  de  recomendação  pode  ser  usado  como  uma estratégia complementar a outros sistemas mais robustos.

### 2.Associação e Modelos Market Basket

Sistemas de recomendação baseados em análise de Associação e Análise de Cesta de Mercado  (Market  Basket)  olham  quase  exclusivamente  em  conteúdo.  Este  tipo  de  análise estatística  baseia-se  apenas  no  mais  simples  dos  cálculos  para  encontrar  itens  que  são frequentementeconsumidos juntos. 

A análise matemática de associação e de market basket éa mesma. Quando os clientes normalmente adquirem os itens ou serviços um de cada vez (como  serviços  bancários)  chamamos  de  Associação.  

Quando  os  clientes  potencialmente compram  várias  coisas  de  uma  só  vez  chamamos  de  Market  Basket.  Assim,  a  Análise  da Associação é realizada ao nível do cliente, enquanto a Análise de Market Basket é conduzida ao nível da transação.

Existem três etapas principais neste processo de análise:

1.Avaliar  a  força  da  relação  entre  cada  um  de  seus  produtos  e  todos  os  outros produtos que você oferece usando os algoritmos de associação.

2.Identificar  aqueles  pares  que  têm  afinidade  muito  forte  (tipicamente  uma pontuação de afinidade de 2 ou superior). Por exemplo, um cliente com um cartão de  crédito  pode  ter  duas  ou três  vezes  mais  probabilidade  de  adquirir  um empréstimo do que um cliente selecionado ao acaso.

3.Criar uma oferta personalizada para clientes que têm um produto (de um par de produtos fortemente associados), mas não o outro.

Vantagens:
•É extremamente simples e rápido.

•Funcionará com bases de clientes muito pequenas. 

•O conhecimento do cliente eseu relacionamento com produtos e serviços não é necessário. 

•A preparação de dados é mínima. •Associação e Market Basket Analysis são normalmente o método mais rentável para criar ofertas personalizadas

