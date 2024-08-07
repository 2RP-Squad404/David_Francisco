## ENGENHARIA DE DADOS
sobre essa area podemos tirar uma conclusao que ela tem uma grande importancia para todas as empresas pelo fato de que um engenheiro de dados fica resposavel por coletar dados,segurança deles garantido que tudo esteja da maneira mais efiente e segura garantindo um armazenamento seguro. ele tambem é responsavel por trabalhar na infraestrutura que seriam a garantia de um bom sinal da rede,um bom software e a parte de harware.
tambem esta presente na manuteção do sistema,amazenar grandes dados dentro de data lake ou data warehouse que seriam locais onde a empresa paga por esse serviço tendo custos de acordo com o que é necessario. 
podemos ver tambem a importancia e a diferença entre data lake e data warehouse.
um data lake consegue armazenar qualquer tipo de dado sendo eles estruturados ou nao, e tem um custo menor, ja um data warehouse ele só aceita dados estruturados,organizados que antes de serem armazenados eles passam por um filtro chamado ETL que servem para extrair dados de diferentes origens para ai sim poderem ser inseridos dentro do data warehouse e tambem seu custo é maior comparado ao data lake.

## GIT 
Git seria uma ferramenta muito importante para o desenvolvimento de um projeto em equipe, já que ele permite modificar versões daquilo que foi desenvolvido, pois nele você pode criar branches e versioná-las.

## GITFLOW
O que seria Gitflow? É a maneira como você gerencia as branches para ordenar as etapas do projeto e também seria uma boa prática pelo fato de deixar um projeto mais profissional. É um método muito importante e essencial para o desenvolvimento de um projeto. Através dele, podemos informar o que estamos fazendo através do histórico dentro do Git, onde podemos alterar e informar suas mudanças dentro de features (versões do programa) criadas de acordo com o que você está trabalhando. Por exemplo, uma equipe que está desenvolvendo um jogo: cada um deve criar uma feature (branch) com o nome do que está trabalhando e, assim que ele criar essa feature, deve informar a equipe através do campo chamado "projects" e selecionar como "in progress". Depois de finalizada, deve subir para a "development". Logo após a etapa de subir para a development, você deve excluir a branch que foi criada. E, após garantir que foi feito o pull request e a confirmação do merge para a develop, você deve subir para a release, garantindo que está tudo certo para subir para a main ou a master, que seria a branch principal."



## BIG DATA
É uma area de conhecimento que está cada vez mais se atualizando de acordo com o crescimento e as necessidades das grandes empresas, que precisam armazenar um grande número de dados e informá-los em tempo real, além de gerar insights que servem para descobrir dados importantes e analisar possíveis anomalias. Isso é possível porque é uma ferramenta que recebe grandes volumes de dados em alta velocidade. A palavra "insights" se refere a percepções ou entendimentos valiosos.

Uma grande vantagem do big data é a capacidade de receber vários tipos de dados, sejam eles estruturados, semi-estruturados e não estruturados. Por exemplo, uma empresa de streaming precisa receber dados em tempo real, conhecidos como "dados quentes". Esses dados necessitam de uma ferramenta rápida. Porém, essa é uma das dificuldades encontradas no big data, devido ao fato de armazenar grandes volumes de dados em tempo real.

Alguns exemplos de desafios ao utilizar o big data incluem:

Armazenamento: Gerenciar e armazenar grandes volumes de dados de maneira eficiente.
Processamento: Processar rapidamente grandes quantidades de dados para extrair insights em tempo real.
Privacidade e Segurança: Proteger dados sensíveis e garantir a conformidade com regulamentações de privacidade.
Qualidade dos Dados: Garantir que os dados sejam precisos, completos e livres de erros, além de identificar anomalias, dado o grande volume de dados recebidos.
É importante destacar que plataformas de Big Data, como Apache Spark, bancos de dados NoSQL (por exemplo, MongoDB, Cassandra), e ferramentas de visualização de dados têm ganhado popularidade.

## MODELAGEM DE DADOS 

a modelagem de dados seria o processo de quando voce obtem varios tipos de dados sendo eles: semi-estruturados e nao estruturados então voce pode converte-los para dados estruturados para facilitar a realização de uma busca de dados, tambem conhecidas como as (queries) em nosso periodo da faculdade   usamos o programa POSTGRESQL que seria para banco de dados relacional que utiliza tabelas, linhas e colunas para armazenar dados. Ele segue a norma SQL e requerem um modelo de dados estruturado e normalizado, tambem dentro dele voce tem suporte para JSON: Embora seja um banco de dados relacional, PostgreSQL suporta tipos de dados JSON e JSONB, permitindo o armazenamento e a consulta de dados semiestruturados. que serve para fazer buscas(query).
e para banco de dados NOSQL utilizamos o MONGODB que utiliza documentos no formato BSON (uma extensão binária de JSON) para armazenar dados. Cada documento pode ter uma estrutura diferente, oferecendo flexibilidade na modelagem de dados e por ele oferecer essa flexibilidade tem sua desvantagem tambem que seria para aplicações que requerem consistência de dados rigorosa ja que ele não é tão garantido quanto um banco de dado relacional.
Sem Esquema Fixo: MongoDB não requer um esquema definido, permitindo que os documentos dentro da mesma coleção tenham estruturas diferentes.
agora um exemplo de trabalho usando banco de dado relacional dentro do POSTGRESQL
uma biblioteca precisa de um sistema de controle para saber quantidade de livros, seus generos,livros novos,preços. nesse caso usaremos da seguinte forma (SELECT * FROM livros WHERE ano > 1990 ) nesse exemplo ele usa o comando SELECT que seria selecionar e com o simbolo * indica que ele esta buscando todos os dados da tabela onde voce precisa e no caso usaria o comando WHERE,que serve para expecificar aonde voce quer fazer a busca então com o comando WHERE voce coloca o filtro ano que seria uma indicação que vc quer fazer uma busca por livros e o ano que voce quer.     