
Este projeto contém os requisitos realizados por _[Bruno Lopes Palmeira](https://www.linkedin.com/in/bruno-palmeira-001742146/)_ enquanto estudava na [Dio](https://www.dio.me/)

# Project MySQL  - One For All

Neste projeto utilizei uma tabela inspirada no Banco de Dados do Spotify (SpotifyClone) para revisar e e consolidar conceitos 
de normalização e execução de queries com o intuito de encontrar as informações solicitadas.

---


 ## Escopo do Projeto
 
 ** 1 **
 
 - Crie um banco com o nome de SpotifyClone.
 - Providencie as queries necessárias para criar tabelas normalizadas que atendam aos requisitos descritos na seção anterior;
 - Providencie as queries necessárias para popular as tabelas de acordo com os dados listados na seção anterior;
 - Crie um arquivo de configurações desafio1.json, que mapeará em qual tabela e coluna se encontram as informações necessárias para a avaliação automatizada deste desafio.
 
 ** 2 **
 
 - Crie uma QUERY que exiba três colunas:

1. A primeira coluna deve exibir a quantidade total de canções. Dê a essa coluna o alias "cancoes".

2. A segunda coluna deve exibir a quantidade total de artistas e deverá ter o alias "artistas".

3. A terceira coluna deve exibir a quantidade de álbuns e deverá ter o alias "albuns".

 ** 3 **
 
 - Crie uma QUERY que deverá ter apenas três colunas:

1. A primeira coluna deve possuir o alias "usuario" e exibir o nome da pessoa usuária.

2. A segunda coluna deve possuir o alias "qtde_musicas_ouvidas" e exibir a quantidade de músicas ouvida pela pessoa com base no seu histórico de reprodução.

3. A terceira coluna deve possuir o alias "total_minutos" e exibir a soma dos minutos ouvidos pela pessoa usuária com base no seu histórico de reprodução.

 ** 4 **
 
 - Crie uma QUERY que deve mostrar as pessoas usuárias que estavam ativas no ano de 2021 se baseando na data mais recente no histórico de reprodução.

1. A primeira coluna deve possuir o alias "usuario" e exibir o nome da pessoa usuária.

2. A segunda coluna deve ter o alias "condicao_usuario" e exibir se a pessoa usuária está ativa ou inativa.
 
 ** 5 **
 
 - Estamos fazendo um estudo das músicas mais tocadas e precisamos saber quais são as duas músicas mais tocadas no momento. Crie uma QUERY que possua duas colunas:

1. A primeira coluna deve possuir o alias "cancao" e exibir o nome da canção.

2. A segunda coluna deve possuir o alias "reproducoes" e exibir a quantidade de pessoas que já escutaram a canção em questão.

 ** 6 **
 
 - Tendo como base o valor dos planos e o plano que cada pessoa usuária cadastrada possui no banco, queremos algumas informações sobre o faturamento da empresa. Crie uma QUERY que deve exibir quatro dados:

1. A primeira coluna deve ter o alias "faturamento_minimo" e exibir o menor valor de plano existente para uma pessoa usuária.

2. A segunda coluna deve ter o alias "faturamento_maximo" e exibir o maior valor de plano existente para uma pessoa usuária.

3. A terceira coluna deve ter o alias "faturamento_medio" e exibir o valor médio dos planos possuídos por pessoas usuárias até o momento.

4. Por fim, a quarta coluna deve ter o alias "faturamento_total" e exibir o valor total obtido com os planos possuídos por pessoas usuárias.

 ** 7 **
 
 - Mostre uma relação de todos os álbuns produzidos por cada pessoa artista, com a quantidade de seguidores que ela possui, de acordo com os detalhes a seguir. Para tal, crie uma QUERY com as seguintes colunas:

1. A primeira coluna deve exibir o nome da pessoa artista, com o alias "artista".

2. A segunda coluna deve exibir o nome do álbum, com o alias "album".

3. A terceira coluna deve exibir a quantidade de pessoas seguidoras que aquela pessoa artista possui e deve possuir o alias "seguidores".

 ** 8 **
 
 - Mostre uma relação dos álbuns produzidos por um artista específico, neste caso "Walter Phoenix". Para isto crie uma QUERY que o retorno deve exibir as seguintes colunas:

1. O nome da pessoa artista, com o alias "artista".

2. O nome do álbum, com o alias "album".

 ** 9 **
 
 - Crie uma QUERY que exibe a quantidade de músicas que estão presentes atualmente no histórico de reprodução de uma pessoa usuária específica. Para este caso queremos saber quantas músicas estão no histórico do usuário "Bill" e a consulta deve retornar a seguinte coluna:

1. O valor da quantidade, com o alias "quantidade_musicas_no_historico".

 ** 10 **
 
 - Crie uma QUERY que exiba o nome e a quantidade de vezes que cada canção foi tocada por pessoas usuárias do plano gratuito ou pessoal de acordo com os detalhes a seguir:

1. A primeira coluna deve exibir o nome da canção, com o alias "nome";

2. A segunda coluna deve exibir a quantidade de pessoas que já escutaram aquela canção, com o alias "reproducoes";

3. Seus resultados devem estar agrupados pelo nome da canção e ordenados em ordem alfabética.

 ** 11 **
 
 - Crie uma QUERY que altere o nome de algumas músicas e as ordene em ordem alfabética com as colunas abaixo se baseando nos seguintes critérios:

1. O nome da música em seu estado normal com o alias nome_musica

2. O nome da música atualizado com o alias novo_nome

Critérios

 - Trocar a palavra "Streets" no final do nome de uma música por "Code Review"
 - Trocar a palavra "Her Own" no final do nome de uma música por "Trybe"
 - Trocar a palavra "Inner Fire" no final do nome de uma música por "Project"
 - Trocar a palavra "Silly" no final do nome de uma música por "Nice"
 - Trocar a palavra "Circus" no final do nome de uma música por "Pull Request"
