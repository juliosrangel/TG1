# TG1 - 5º semestre de BD

 

Professor da Disciplina: Giuliano Bertoti 

 

# TG

 

Aluno: Julio Cesar Silva Rangel - 1460281713023

 

Título do TG: Utilização de tecnologia para analise de dados no futebol americano no brasil.


FACULDADE DE TECNOLOGIA DE SÃO JOSÉ DOS CAMPOS
FATEC PROFESSOR JESSEN VIDAL








JULIO CESAR SILVA RANGEL






UTILIZAÇÃO DE TECNOLOGIA PARA ANALISE DE
DADOS NO FUTEBOL AMERICANO NO BRASIL



São José dos Campos
2020


AGRADECIMENTOS


Gostaria de agradecer a minha família, por sempre me apoiar, por estar ao meu lado, sempre
auxiliando, pagando meus estudos, acreditando em meu potencial em todos os momentos,
sem eles não chegaria até aqui.
Gostaria de também agradecer aos professores, por todo ensinamento passado durante as
aulas e auxilio durante o curso. Também aos colegas, que em muitos momentos foram como
professores e me auxiliaram em muitos momentos com ensinamentos, conversas, entre tantas
ajudas.



RESUMO


O intuito do projeto é criar um software para análise de dados para o futebol
americano no brasil, criando um software para a análise dos dados e criação de estatísticas,
que possam ser utilizadas para melhora no desempenho dos atletas, encontrando pontos fracos e potencializando as qualidades 

Palavras-Chave: Futebol Americano; Analise de dados; Brasil.

ABSTRACT


The purpose of the project is to create software for data analysis for football in Brazil, creating software for data analysis and creation of statistics, which can be used to improve athletes’performance, finding weaknesses and enhancing their qualities

Keywords: Football; Data Analysis; Brazil. 

 
1. INTRODUÇÃO 
Desde pequeno tenho interesse por esportes, de todos os tipos, sejam eles futebol, basquete,
automobilismo, tênis, handebol, wrestling, entre tantos outros.
No canal de esportes ESPN e no canal de esportes BandSports, eram transmitidos jogos de
futebol americano algumas vezes acompanha, porém não entendia muito do que acontecia,
não sabia o porquê daqueles rapazes muito grandes bravamente batalhando para correr com
uma bola oval.
Em 3 de fevereiro de 2008 estava assistindo televisão, até que chego ao canal Band, lá estava
passando a final do torneio americano de futebol americano, o famoso Super Bowl, na ocasião
disputado por New York Giants e New England Patriots, após isso adquiri um carinho pelo
esporte.
No ano de 2016, fiz uma seletiva para participar do time de futebol americano da cidade, o
São José Jets, onde fui aprovado e fiz parte do time por 2 anos, nesses dois anos, continuei
acompanhando a liga americana, a NFL, e percebi o quanto de tecnologia para análise de
dados eram utilizadas para melhora no desempenho. A realidade no esporte aqui no Brasil era
outra, ainda sendo um esporte amador, o uso da tecnologia era nulo, assim me motivando a
desenvolver alguma tecnologia que possa auxiliar o esporte aqui no brasil, mais
especificamente na minha cidade.
O futebol americano é um esporte de muita análise, onde as estatísticas e os dados são muito
importantes, a análise desses dados podem ser pontos que podem ajudar na evolução de um
atleta ou time, seja para encontrar um ponto de fraqueza e evoluir nesse ponto, seja para
encontrar uma qualidade explora-la nos jogos.

1.1. Objetivos do Trabalho 
O objetivo geral deste trabalho é auxiliar a evoluçao do futebol americano no Brasil, auxiliando com a tecnologia.
Para a consecução deste objetivo foram estabelecidos os objetivos específicos:
•	Analise dos dados 
•	Encontrar pontos fortes
• Encontrar pontos fracos dos adversarios


2. FUNDAMENTAÇÃO TÉCNICA

O objetivo desse capitulo é apresentar as tecnologias e processos que serão utilizados para a construção do sistema.

2.1 TECNOLOGIAS

As tecnologia usadas neste projeto serão:

-Java para desenvolvimento do Back-end.

-Vue.js onde sera desenvolvido o Front-end.

-MySQL onde sera desenvolvido o banco de dados.

-Spring Boot para realizar as configurações e publicações da aplicação.


3. DESENVOLVIMENTO

3.1 - Modelagem do sistema 

O modelo utilizado nesse projeto sera o padrão MVC(Model - View - Controller), onde basicamente um usuário faz uma requisição, que passa pelo controller é encaminhada ao model, e após isso é devolvida ao view para o retorno ao usuário que fez a requisição inicial.


3.2 - Banco de dados 

O banco de dados utilizado será o MySQL, que é um SGBD(Sistema Gerenciador de Banco de Dados),  um dos mais populares no mercado atual, teve origem com a empresa AB, que posteriormente foi comprada pela Sun e posterior mente foi comprada pelo Oracle, que hoje é a proprietária da aplicação.

3.3 - Projeto da aplicação

A ideia do sistema é a analise de dados de jogadas, para que seja feita uma resposta onde seja possível analisar as jogadas com mais índice de acerto e também as com baixo grau de funcionalidade, para que assim ocorra sua melhora.
Neste projeto serão 3 perfis utilizados, o de administrador, comissão técnica e jogador. Onde o administrador poderá ter acesso a todos os dados, a comissão técnica terá acesso a todos os dados e também poderá fazer a entrada de dados para que o banco possa ser alimentado com novos dados, porém apenas de um determinado time e o jogador poderá ter acesso apenas a seus dados e números, não podendo assim alimentar o banco com novos dados.


