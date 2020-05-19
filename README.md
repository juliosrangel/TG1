# TG1 - 5º semestre de BD

 

Professor da Disciplina: Giuliano Bertoti 

 

# TG

 

Aluno: Julio Cesar Silva Rangel - 1460281713023
Orientador: nome

 

Título do TG: Utilização de tecnologia para analise de dados no futebol americano no brasil.

 

(ISSO NÃO PRECISA IR NO README.MD - É SÓ UMA INSTRUÇÃO: DAQUI EM DIANTE SIGA EXATAMENTE O MODELO DE TG DE BD A PARTIR DO CAPÍTULO 1 - AQUELA PARTE DE CAPAS VOCÊ PODE PREENCHER E GUARDAR PARA VOCÊ - AQUI NO GITHUB QUERO A PARTIR DO CAPÍTULO 1)

 FACULDADE DE TECNOLOGIA DE SÃO JOSÉ DOS CAMPOS
FATEC PROFESSOR JESSEN VIDAL








JULIO CESAR SILVA RANGEL






UTILIZAÇÃO DE TECNOLOGIA PARA ANALISE DE
DADOS NO FUTEBOL AMERICANO NO BRASIL




















São José dos Campos
2020

 
 
JULIO CESAR SILVA RANGEL








UTILIZAÇÃO DE TECNOLOGIA PARA ANALISE DE DADOS NO FUTEBOL AMERICANO NO BRASIL





Trabalho de Graduação apresentado à Faculdade de Tecnologia de São José dos Campos, como parte dos requisitos necessários para a obtenção do título de Tecnólogo em Banco de Dados.


Orientador: 








São José dos Campos
2020 



Dados Internacionais de Catalogação-na-Publicação (CIP)
Divisão de Informação e Documentação





 





REFERÊNCIA BIBLIOGRÁFICA

SOBRENOME, Nome do Aluno. Título do Trabalho de Graduação. 20XX. 999f. Trabalho de Graduação - FATEC de São José dos Campos: Professor Jessen Vidal.







CESSÃO DE DIREITOS

NOME(S) DO(S) AUTOR(ES): Nome Completo do Aluno 
TÍTULO DO TRABALHO: Título do Trabalho de Graduação 
TIPO DO TRABALHO/ANO: Trabalho de Graduação/20XX.


É concedida à FATEC de São José dos Campos: Professor Jessen Vidal permissão para reproduzir cópias deste Trabalho e para emprestar ou vender cópias somente para propósitos acadêmicos e científicos. O autor reserva outros direitos de publicação e nenhuma parte deste Trabalho pode ser reproduzida sem a autorização do autor.





_____________________________________
Nome Completo do Autor
Endereço do Autor
XXXXX-XXX, Cidade – Estado	
NOME DO AUTOR




TÍTULO DO TRABALHO DE GRADUAÇÃO
 


Trabalho de Graduação apresentado à Faculdade de Tecnologia de São José dos Campos, como parte dos requisitos necessários para a obtenção do título de Tecnólogo em Banco de Dados.








__________________________________________________________________
Titulação, Nome do Componente da Banca - Sigla da Instituição


___________________________________________________________________
Titulação, Nome do Componente da Banca - Sigla da Instituição


__________________________________________________________________
Titulação, Nome do Orientador – Sigla da Instituição Titulação


__________________________________________________________________
Nome do Coorientador (se existir) - Sigla da Instituição





_____/_____/_____

DATA DA APROVAÇÃO (dia da banca)
Dedicatória (opcional)













































AGRADECIMENTOS



Na página de agradecimentos o autor dirige palavras de reconhecimento àqueles que contribuíram para a elaboração do trabalho. O conteúdo não deve ultrapassar uma página e por isso, é necessário que ele seja sucinto e objetivo.
O texto deve ser escrito em Times New Roman, Tamanho 12, Alinhamento Justificado, Espaçamento entre linhas de 1,5 linhas e com recuo de parágrafo de 1,25 cm.











































































 
RESUMO


O intuito do projeto é criar um software para análise de dados para o futebol
americano no brasil, criando um software para a análise dos dados e criação de estatísticas,
que possam ser utilizadas para melhora no desempenho dos atletas, encontrando pontos fracos e potencializando as qualidades 

Palavras-Chave: Futebol Americano; Analise de dados; Brasil.
ABSTRACT


The purpose of the project is to create software for data analysis for football in Brazil, creating software for data analysis and creation of statistics, which can be used to improve athletes’performance, finding weaknesses and enhancing their qualities

Keywords: Football; Data Analysis; Brazil. 


























 


LISTA DE FIGURAS

Figura 1 - Proposta metodológica	17








































LISTA DE TABELAS


Tabela 1 - População de 15 a 24 anos de idade	18































LISTA DE ABREVIATURAS E SIGLAS



ARF	Árvore da Realidade Futura
APS	Advanced Planning and Scheduling
ARA	Árvore da Realidade Atual
B2B	Business to Business
CD		Centro de Distribuição
CEPAA 	Council on Economic Priorities Accreditation Agency
































LISTA DE SÍMBOLOS



dab		Distância Euclidiana
O(n)	Ordem de um Algoritmo





































SUMÁRIO

1. INTRODUÇÃO	15
1.1. Objetivos do Trabalho	15
1.2. Conteúdo do Trabalho	15
2. FUNDAMENTAÇÃO TÉCNICA	17
2.1. Título 2.1	17
2.2. Título 2.2	17
3. DESENVOLVIMENTO	18
3.1. Arquitetura do Sistema	18
3.2. Título 3.2	18
4. RESULTADOS	19
4.1. Título 4.1	19
4.2. Título 4.2	19
5. CONSIDERAÇÕES FINAIS	20
5.1. Contribuições	20
5.2. Trabalho Futuros	20
REFERÊNCIAS	21
APÊNDICE A/ANEXO A – EXEMPLO DE APÊNDICE/ANEXO	23
Como deve ser a formatação das Figuras, Tabelas e Equações no trabalho	24
Como deve ser mencionada as Siglas no trabalho	26
Como deve ser feitas as citações no trabalho	26
Como utilizar as referências bibliográficas no texto do trabalho	27



 
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


1.2. Conteúdo do Trabalho
O presente trabalho está estruturado em seis Capítulos, cujo conteúdo é sucintamente apresentado a seguir:
No Capítulo 2 é feita a fundamentação das tecnologias.
O Capítulo 3 apresenta o desenvolvimento da solução.
No Capítulo 4 são apresentados os resultados.
O Capítulo 5 apresenta as considerações finais  deste trabalho a partir da análise dos resultados obtidos.


 


# 1ª Quinzena de maio

 

(coloque aqui tudo que você fez referente ao capítulo 1 no formato exato de BD)

 

# 2ª Quinzena de maio

 

(coloque aqui tudo que você fez referente ao capítulo 2 no formato exato de BD)

 

# 1ª Quinzena de junho
 
(coloque aqui tudo que você fez referente ao capítulo 3 no formato exato de BD)

 

# 2ª Quinzena de junho

 

(coloque aqui tudo que você fez referente ao capítulo 3 no formato exato de BD) + crie um pasta chamada "Desenvolvimento" e coloque o início do código

 

# 1ª Quinzena de julho

 

(coloque aqui tudo que você fez referente ao capítulo 3 no formato exato de BD) + atualize a continuação do código
