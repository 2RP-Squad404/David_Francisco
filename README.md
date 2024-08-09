## ENGENHARIA DE DADOS
sobre essa area podemos tirar uma conclusao que ela tem uma grande importancia para todas as empresas pelo fato de que um engenheiro de dados fica resposavel por coletar dados,segurança deles garantido que tudo esteja da maneira mais efiente e segura garantindo um armazenamento seguro. ele tambem é responsavel por trabalhar na infraestrutura que seriam a garantia de um bom sinal da rede,um bom software e a parte de harware.
tambem esta presente na manuteção do sistema,amazenar grandes dados dentro de data lake ou data warehouse que seriam locais onde a empresa paga por esse serviço tendo custos de acordo com o que é necessario. 
podemos ver tambem a importancia e a diferença entre data lake e data warehouse.
um data lake consegue armazenar qualquer tipo de dado sendo eles estruturados ou nao, e tem um custo menor, ja um data warehouse ele só aceita dados estruturados,organizados que antes de serem armazenados eles passam por um filtro chamado ETL que servem para extrair dados de diferentes origens para ai sim poderem ser inseridos dentro do data warehouse e tambem seu custo é maior comparado ao data lake.

## GIT 
Git seria uma ferramenta muito importante para o desenvolvimento de um projeto em equipe, já que ele permite modificar versões daquilo que foi desenvolvido, pois nele você pode criar branches e versioná-las.

## GITFLOW
O que seria Gitflow? É a maneira como você gerencia as branches para ordenar as etapas do projeto e também seria uma boa prática pelo fato de deixar um projeto mais profissional.  mudanças dentro de features (versões do programa) criadas de acordo com o que você está trabalhÉ um método muito importante e essencial para o desenvolvimento de um projeto. Através dele, podemos informar o que estamos fazendo através do histórico dentro do Git, onde podemos alterar e informar suasando. Por exemplo, uma equipe que está desenvolvendo um jogo: cada um deve criar uma feature (branch) com o nome do que está trabalhando e, assim que ele criar essa feature, deve informar a equipe através do campo chamado "projects" e selecionar como "in progress". Depois de finalizada, deve subir para a "development". Logo após a etapa de subir para a development, você deve excluir a branch que foi criada. E, após garantir que foi feito o pull request e a confirmação do merge para a develop, você deve subir para a release, garantindo que está tudo certo para subir para a main ou a master, que seria a branch principal."



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


A modelagem de dados é o processo de obter vários tipos de dados, sendo eles: semi-estruturados, estruturados e não estruturados, e modelá-los por etapas para se trabalhar de forma correta, já que o processo de modelagem de dados é composto pelas etapas de modelo conceitual, lógico e físico. Depois de obter as informações, você pode desenvolver modelos: lógico, físico ou conceitual, dependendo das necessidades da empresa que for armazená-los.

MODELO CONCEITUAL - Essa é a etapa onde os dados são organizados em tabelas para se relacionarem, indicando sua cardinalidade, como por exemplo: 1:1, N:N, N:1 ou 1:N.
. A cardinalidade depende de como essas tabelas se relacionam. Por exemplo, o ID serve para indicar um único valor, e, em outra tabela, uma PK (Primary Key) é convertida em uma chave estrangeira (Foreign Key - FK).

MODELO LÓGICO - Esta etapa é praticamente uma conversão do modelo conceitual para o lógico. Depois da etapa do modelo conceitual, você poderá indicar o que seria chave secundária e sua cardinalidade.

MODELO FÍSICO - Nessa etapa, você já pode classificar os itens da tabela, definindo se são variáveis do tipo: INT, DOUBLE, VARCHAR, TEXT, entre outros. Também pode fazer a manutenção usando comandos como os exemplos abaixo:

ALTER TABLE Clientes

RENAME COLUMN Telefone TO Telefone_Principal

ALTER TABLE Clientes

DROP COLUMN Telefone

DOUBLE preço (10,2)   

INT quantidade de livros(60)

Nesse caso, estamos nos referindo a pequenos dados. Já quando se trata de uma empresa que necessita de mais espaço para armazenar um número muito grande de dados (Big Data), a empresa deve contratar um Data Lake ou até mesmo um Data Warehouse.