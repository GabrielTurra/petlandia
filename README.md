# Petlândia
Bem vindos a Petlândia! Sua plataforma dedicada ao amor e fofura dos bichinhos.

Estou construindo essa plataforma com o objetivo de  estudar e aplicar alguns conceitos de programação/design de software e quem sabe dar vida a esse projeto futuramente.
Aqui listarei todas as possiveis features e seus objetivos dentro do meu plano de estudos.

# Descritivo
O objetivo da plataforma é realizar a conexão entre doadores e vendedores com seu público alvo.

Pessoas podem se cadastrar na plataforma através de seu CPF e com isso podem procurar ou divulgar os animaiszinhos.

ONGs podem se cadastrar na plataforma através de um CPNJ e fazer a divulgação de seus animais disponiveis. Elas poderam cadastrar todas as suas unidades e indicar em qual unidade cada animal está disponível.
Também será possivel para as ONGs definirem uma taxa de adoção e realizar o pagamento da mesma pela plataforma.
ONGs poderão criar eventos, como feiras de adoção e divulga-las dentro da propria plataforma para os usuários. Esses eventos possuirão data definida (dia unico ou periodo), horario de funcionamento, local e os animais disponiveis além de também ser possivel personalizar a taxa de adoção para esses eventos.

Canis e gatis privados, também terão seu espaço na plataforma.
Para se cadastrar deverão ter um CPNJ, cadastrar todas as suas unidades e indicar em qual unidade cada animal está disponível.
Para esses usuários teremos uma arvore genealogica disponivel, onde cada animal vai se relacionar com seus parentes com o intuito de comprovar a linhagem.
Também será possivel subir os exames e prêmios de cada animal, para reforçar ainda mais a força da linhagem.
Cada animal aqui deverá possuir um certificado CBCK para evitar criação desrregulamentadas.
Quando o nascimento ocorrer será gerada uma ninhada com a quantidade de filhotes e quando chegar o momento da venda, deverá ser preenchido essa informação antes da publicação dos anúncios.
O pagamento poderá ser feito pela plataforma através de alguma API de pagamentos como o Stripe ou mercado pago.

A parte de canis e gatis privados estará disponivel em um sbdominio para separar as coisas e evitar comentarios mal intencionados/informados sobre compra de animais dentro da plataforma.
Para isso, o front-end será construdio utilizando um Design system, que possibilitará manter a identidade visual entre ambos os projetos.

# Sobre as tecnologias
Eu poderia utilizar Next.js para construir 100% da aplicação em monolito, mas como o objtivo é treinar alguns conceitos decidi construir uma API a parte em node com micro-serviços e um front que consumirá esses serviços.
Possivelmente também criarei um aplicativo mobile com React Native, mas por enquanto vamos focar na versão web.

Como o principal objetivo desse projetos são os estudos, o objetivo de cada tecnologia é o seguinte: 
 - A API seguirá o padrão DDD implementando os micro-serviços e 100% focada em ser contruida através da metodologia TDD.
 - O front utilizará Next 13 pois além de atender bem a proposta, também quero implementar os novos conceitos de Server Components.
 - Para preencher o conteúdo editorial da aplicação (aquele que não tem relação com os anuncios e afins, mas são mais estáticos e ajudam no SEO), utilizarei o Contenful como CMS. Dessa maneira teremos uma plataforma para o controle de conteúdo e futuramente também posso pensar em construir um blog para ajudar na divulgação da plataforma pelos mecanismos de busca.
