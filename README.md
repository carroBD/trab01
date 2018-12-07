# TRABALHO 01:  Smart Car - Carro inteligente.
Trabalho desenvolvido durante a disciplina de BD1.

### 1. COMPONENTES<br>
Integrantes do grupo
    <ol>Harrison Sanches: harrison.sanches@gmail.com</ol>
    <ol>João Augusto: joao.augusto1809@gmail.com</ol>
    <ol>Luciano Barboza: luciano.ananias.50@gmail.com</ol>
    <ol>Matheus Comério: matheuscomerior@gmail.com</ol>

### 2.INTRODUÇÃO E MOTIVAÇAO<br>

<p align="justify">O grande número de acidentes nas rodovias brasileiras, e o elevado número de mortes proveniente desse assunto, é um dos grandes problemas existentes no país. Considerado como problema de saúde pública, o Brasil aparece em quinto lugar entre os países recordistas em mortes no trânsito, atrás da Índia, China, EUA e Rússia. Segundo o Ministério da Saúde, em 2015, foram registrados 37.306 óbitos e 204  mil pessoas ficaram feridas. Em 2016, só na microrregião metropolitana no Estado do Espírito Santo, foram 23.190 mortes.</div
<br> <p> <img src=https://github.com/carroBD/trab01/blob/master/Imagens/Capturar.PNG/><br></p>
<p align="justify">As causas dos acidentes são variadas. Segundo o portal do trânsito brasileiro, as maiores causas destes acidentes são: Excesso de velocidade; Desrespeito à sinalização; Ingestão de bebidas alcoólicas e, liderando, Imprudência.
Acerca da imprudência, estão diversos fatores, principalmente a não revisão veicular e falhas mecânicas dos componentes veiculares, provenientes do descaso dos motoristas com seus veículos. E é em cima desse problema que o sistema “Smart Car” visa colaborar. O sistema tem como finalidade gerenciar os componentes mecânicos do carro (giro do motor, pistão, pneus, precisão dos controles) a fim de gerar dados sobre esses componentes e analisar possíveis falhas ocorridas nas peças dos veículos. O sistema visa atuar também em cima do dinamismo acerca do tempo da sociedade contemporânea , impactando no ganho de tempo no cotidiano do usuário, possibilitando, por exemplo, que o usuário do sistema, ao ser notificado de uma falha de um componente, possa agendar diretamente, com um mecânico de sua escolha, uma revisão ou troca do componente, agilizando sua rotina e trabalho de vistoria do mecânico, evitando perda de tempo para ambas as partes. Para isso, o sistema contará com sensores de controle, gerando dados sobre os componentes, e possibilitará o cadastro do carro e de mecânicos especializados escolhidos e cadastrados pelo cliente para contato. O sistema notificará, de forma simples e  satisfatória, uma falha de algum componente e deverá armazenar esses dados de falhas em bancos de dados para possíveis novas análises.</div> 

### 3.MINI-MUNDO<br>
<p align="justify">O sistema “Smart Car” proposto tem por objetivo a inspeção e análise  veicular, a fim de gerar análises dos componentes do veículo. Acerca das inspeções, cada carro contará com sensores, cada sensor é associado a um, ou varios outros componente do carro. O carro poderá contar com mais de um sensor e cada carro terá um motorista a ele associado. Cada sensor terá seu nome de identificação, finalidade e identificação associando em qual carro está inserido. Será necessário um cadastro do cliente com nome, cpf e CNH para identificação. No que tange ao carro, será necessário armazenar informações sobre o veículo, como placa, ano, modelo, cor e marca e seus respectivos sensores instalados. Cada carro poderá ter um, e somente um, motorista associado. O sistema deve ser capaz de notificar o usuário de forma simples e clara, a fim de especificar a possível falha de algum componente, através de um esquema de cores simplificado, a situação do componente do carro. O sistema deve realizar cadastro de mecânicos, escolhidos pelo usuário, a fim de estabelecer um contato entre os dois agentes. Deverá permitir também um contato de forma simples e direta, com a possibilidade de cadastro de mais de um mecânico por cliente. O sistema não ficará responsável pelo controle de peças por parte do mecânico, o mesmo apenas estabelecerá um contato entre cliente-mecânico, a fim de ambos chegaram a um consenso para possível revisão/troca do componente. O sistema não fornecerá dados do componentes instalados no carro do motorista, por questão de privacidade e risco de possíveis fraudes nos componentes ou na hora do serviço prestado. No momento do contato, será informado apenas a hora, data e respectivo componente que ocorreu a falha. O sistema contará com diferenciação no cadastro entre ser cliente ou mecânico.a fim de proporcionar telas diferentes para ambos. Na tela do mecânico contará apenas os clientes que o adicionaram ao usar o programa. Será necessário captar os dados como Nome e nome da oficina para controle e segurança para os clientes. Já a tela do motorista contará com dados dos sensores, sensores instalados, carros cadastrados, mecânicos cadastrados e área para contato com o mecânico que assim desejar.</div> 



### 4.RASCUNHOS BÁSICOS DA INTERFACE (MOCKUPS)<br>
https://github.com/carroBD/trab01/blob/master/arquivos/TELA%20BD.pdf
    
    
    
#### 4.1 QUAIS PERGUNTAS PODEM SER RESPONDIDAS COM O SISTEMA PROPOSTO?
   O sistema poderá contar com uma série de dados acerca de gerarem metadados para novas avaliações, seja sobre o modelo do carro, perfil do motorista ou disponibilidade do mecânico. Assim, sistema proposto servirá para adiquirir e gerar relatórios, como por exemplo os citados abaixo:
   - Relatório geral sobre a situação do carro do cliente
   - Relatório de quais componentes do carro quebram com mais frequência
   - Relatório acerca da quais mecânicos estão mais disponíveis
   - Relatório de quais modelos de carro apresentam mais falhas
   - Perfil dos motoristas, relacionando idade com número de falhas nas peças.<br>
   Gráficos para melhores análises poderão ser consultados em: https://github.com/carroBD/trab01/blob/master/RELAT%C3%93RIO%20WITH%20JUPYTER/RELATORIO_JUPYTER.ipynb<br><br>

 
#### 4.2 TABELA DE DADOS DO SISTEMA:
<img src=https://github.com/carroBD/trab01/blob/master/Planilha/Planilha%20BD.xlsx/>
<br><b>"Tabela - SmartCar"</b>
Tabela relacionando entidades e componentes existente no sistema e banco de dados.
    
>## Marco de Entrega 01 em: (30/08/2018)<br>

### 5.MODELO CONCEITUAL<br>
        
<img src=https://github.com/carroBD/trab01/blob/master/Imagens/CONCEITUAL_VERSAOFINALIFES.png/>
    
   
    
        
    
#### 5.1 Validação do Modelo Conceitual
    [Transporte de Carnes]: Rafael dos Anjos, Daniel Comerio,Nicolas Sampaio,Andreas Hermes.
    [Controle de Rotas]: Ana Paula,Italo Vaz,Luma Gonçalvez,Rafael Sampogna.

#### 5.2 DECISÕES DE PROJETO

    DESCRIÇÃO DE ALGUNS ATRIBUTOS<br>
    Nome: O campo é simples. Servirá apenas para armazenar o nome do cliente e não para identificá-lo.
    Nome oficina: Campo simples. Este campo armazenará o nome da oficina pertencente ao mecânico, e não servirá para identificá-la.
    Sexo: Campo Simples.
    CNH: Campo Simples
    Contato: Simples e multivalorado. Pode armazenar no mínimo um contato pra cada motorista/mecânico.
    CNPJ: Simples e determinante. Com esse dado é possível identificar uma única oficina.
    Placa veiculo: Campo simples e determinante. Com a placa é possível especificar o carro procurado.
    Marca: Campo simples.
    Modelo: Campo simples.
    Categoria: Campo simples
    Sensores: Campo simples. Armazena o nome do sensor para diferenciá-lo dos demais, porém pode ser repetido, ou seja, não é determinante.
    Hora_analise: Campo simples
    Data_análise Campo simples.


>## Marco de Entrega 02 em: (13/09/2018)<br>

#### 5.3 DESCRIÇÃO DOS DADOS.]
    PESSOA: TABELA PAI QUE ARMAZENA DADOS DO TIPO PESSOA DO SISTEMA.
        - ID_PESSOA: ID para identificação da pessoa.
        - NOME: Campo que armazena o nome da pessoa.
        - Data_Nascimento: Campo que armazena a data de nascimento da pessoa.
        - Sexo: Campo referente ao Sexo da pessoa.
    
    MOTORISTA: TABELA FILHO QUE HERDA CARACTERÍSTICAS DA TABELA PESSOA PARA DISTIÇÃO E CRIAÇÃO DO USUÁRIO MOTORISTA DO SISTEMA.
        - CNH: Campo que armazena o tipo de CNH do motorista.
    
    MECÂNICO: TABELA FILHO QUE HERDA CARACTERÍSTICAS DA TABELA PESSOA PARA CRIAÇÃO E DISTINÇÃO DO USUÁRIO MECÂNICO DO SISTEMA.
    	- NOME_OFICINA: Campo que armazerna o nome da oficina do mecânico.
    	- CNPJ: Campo que armazena o CPNJ da respectiva oficina do mecânico.
    	- ESPECIALIZAÇÃO: Campo que armazena a especialização do mecânico.
        
    VEÍCULO: TABELA QUE ARMAZENA OS DADOS DO VEÍCULO CADASTRADO POR UM USUÁRIO DO TIPO CLIENTE.
        - PLACA: Campo que armazena a placa de um veículo cadastrado por um usuário do tipo cliente.
        - ID_VEÍCULO Campo que armazena a ID do veículo.
        
    CATEGORIA: TABELA QUE ARMAZENA DADOS SOBRE A CATEGORIA DE TODOS OS CARROS CADASTRADOS NO SISTEMA POR UM USUÁRIO DO TIPO CLIENTE.
        - ID_CATEGORIA: iD para identificação da categoria.
        - TIPO_CATEGORIA: Tabela que armazena o tipo da categoria.	
        
    MODELO: TABELA QUE ARMAZENA OS MODELOS DE VEÍCULOS DO SISTEMA
        - ID_MODELO: ID para identificação do modelo do veículo:
        - MODELO_VEÍCULO: Campo que armazena o modelo do veículo.
        - ANO_VEÍCULO: Campo que armazena o ano do modelo do veículo.
        - COR: Campo que armazena a cor do modelo do veículo
    
    MARCA: TABELA QUE ARMAZENA AS MARCAS DE VEÍCULOS DO SISTEMA
        - ID_MARCA: ID para identificação da marca do veículo:
        - MARCA_VEÍCULO: Campo que armazena marca do veículo.
   
    CONTATO: TABELA QUE ARMAZENA O CONTATO DO CLIENTE
        - CONTATO: Campoq ue armazena contato do cliente.
        - ID_CONTATO: Id para identificação do contato.
    
    TIPO_CONTATO: TABELA QUE ARMAZENA O TIPO DE CONTATO DO CLIENTE
        - TIPO_CONTATO: Campoq ue armazena o tipo de contato.
        - ID_TIPO_CONTATO: Id para identificação do tipo de contato.
 
    SENSORES: TABELA QUE ARMAZENA OS DADOS SOBRE OS SENSORES
        - NOME_SENSOR: Campo que armazena o nome do sensor.
        - ID_SENSOR: ID para identificação do sensor.
        - DESCRIÇÃO: Campo que descreve a funcionalidade/descrição/característica do sensor.
    
    TIPO_SENSOR: TABELA QUE ARMAZENA OS TIPOS DE SENSORES
        - TIPO_SENSOR: Campo que armazena o tipo de sensor
        - ID_TIPO_SENSOR: ID para identificação do tipo de sensor.
    
    HISTÓRICO: TABELA QUE ARMAZENA O HISTÓRICO DAS ANÁLISES GERADAS POR CADA SENSOR.
        - DATA_ANALISE: Campo que armazena a data da analise do sensor
        - HORA_ANALISE: Campo que armazena o horario da analise do sensor	
        - ID_HISTÓRICO: ID para identificação da informação gerada pelo sensor.
    
    GERAM: TABELA QUE ARMAZENA O ESTADO DA PEÇA:
    	- ESTADO_PEÇA: Campo que armazena o estado da peça. O campo é binário.
    
    CONTRATA: TABELA QUE ARMAZENA OS DADOS SOBRE A CONTRATAÇÃO E CHAMADO DOS MECÂNICOS PELOS MOTORISTAS DO SISTEMA
        - HORA_CONTRATA: Campo que armazena a hora da contratação.
        - DATA_CONTRATA: Campo que armazena a data da contratação.
        - ID_CONTRATA: Id para identificação da contratação.
    
    
    
### 6	MODELO LÓGICO<br>
<img src=https://github.com/carroBD/trab01/blob/master/Imagens/LOGICO_VERSAOFINALIFES.png/>

### 7	MODELO FÍSICO<br>
<a href="https://github.com/carroBD/trab01/blob/master/Modelo%20Fisico%20.SQL.txt">Modelo Físico</a>       
        
### 8	INSERT APLICADO NAS TABELAS DO BANCO DE DADOS<br>

#### 8.1 DETALHAMENTO DAS INFORMAÇÕES
      
 <a href="https://github.com/carroBD/trab01/blob/master/Script%20Inser%C3%A7%C3%A3o%20SQL.txt">Script de Inserção</a>


#### 8.2 INCLUSÃO DO SCRIPT PARA CRIAÇÃO DE TABELAS E INSERÇÃO DOS DADOS
<a href="https://github.com/carroBD/trab01/blob/master/Script%20%20Cria%C3%A7%C3%A3o%20%2BInser%C3%A7%C3%A3o%20SQL.txt">Script de Criação + Inserção</a>

#### 8.3 INCLUSÃO DO SCRIPT PARA EXCLUSÃO DE TABELAS EXISTENTES, CRIAÇÃO DE TABELA NOVAS E INSERÇÃO DOS DADOS
<a href="https://github.com/carroBD/trab01/blob/master/Criando%20um%20banco%20do%20zero.txt">Script de Criação do Banco de Dados do zero</a>

>## Marco de Entrega 03 em: (27/09/18) <br>

### 9	TABELAS E PRINCIPAIS CONSULTAS<br>
    OBS: Incluir para cada tópico as instruções SQL + imagens (print da tela) mostrando os resultados.<br>
#### 9.1	CONSULTAS DAS TABELAS COM TODOS OS DADOS INSERIDOS (Todas) <br>
SELECT * FROM PESSOA <br>
	<img src = https://github.com/carroBD/trab01/blob/master/SELECTS%20NOVOS/PESSOA%201.PNG/>

<br><br>
SELECT * FROM CONTATO<br>
	<img src = https://github.com/carroBD/trab01/blob/master/SELECTS%20NOVOS/CONTATO.PNG/>
<br><br>
SELECT * FROM TIPO_CONTATO<br>
	<img src= https://github.com/carroBD/trab01/blob/master/SELECTS%20NOVOS/TIPO_CONTATO.PNG/>
	<br><br>
SELECT * FROM VEICULO<br>
	<img src = https://github.com/carroBD/trab01/blob/master/SELECTS%20NOVOS/VEICULO.PNG/>
<br>
<br>
SELECT * FROM MODELO<br>
	EDITAR MODELO
<br>
<br>
SELECT * FROM MARCA<br>
	<img src = https://github.com/carroBD/trab01/blob/master/SELECTS%20NOVOS/MARCA.PNG/><br>
<br>
<br>
SELECT * FROM CATEGORIA<br>
	<img src = https://github.com/carroBD/trab01/blob/master/SELECTS%20NOVOS/CATEGORIA.PNG/>
<br>
<br>
SELECT * FROM SENSORES<br>

	<img src = https://github.com/carroBD/trab01/blob/master/SELECTS%20NOVOS/SENSOR.PNG/>
<br>
<br>
SELECT * FROM TIPO_SENSOR<br>
	<img src = https://github.com/carroBD/trab01/blob/master/SELECTS%20NOVOS/TIPO_SENSOR.PNG/>
<br>
<br>
SELECT * FROM GERAM<br>
	<img src = https://github.com/carroBD/trab01/blob/master/SELECTS%20NOVOS/GERAM.PNG/>
<br>
<br>
SELECT * FROM HISTORICO<br>
	<img src = https://github.com/carroBD/trab01/blob/master/SELECTS%20NOVOS/HISTORICO.PNG/><br>
<br>
<br>

#### 9.2	CONSULTAS DAS TABELAS COM FILTROS WHERE (Mínimo 4)<br>

SELECT *FROM MODELO 
	WHERE COR = 'PRETO';<br>
<img src = https://github.com/carroBD/trab01/blob/master/WHERE%20NOVOS/MODELO%20PRETO.PNG/>
	<br><br>
SELECT *FROM PESSOA
	WHERE CNH ='AB'<br>
<img src = https://github.com/carroBD/trab01/blob/master/WHERE%20NOVOS/CNH%20AB.PNG/>
	<br><br>
SELECT *FROM PESSOA 
	WHERE NOME = 'Luciano'<br>
<img src = https://github.com/carroBD/trab01/blob/master/WHERE%20NOVOS/PESSOA%20LUCIANO.PNG/>
	<br><br>
SELECT *FROM MODELO
	WHERE ANO_VEICULO = 2014;<br>
<img src = https://github.com/carroBD/trab01/blob/master/WHERE%20NOVOS/MODELO%202014.PNG/>
	<br>
	<br>	
SELECT FROM CONTATO 
	WHERE FK_TIPO_CONTATO_ID_TIPO_CONTATO = 1;<br>
<img src = https://github.com/carroBD/trab01/blob/master/WHERE%20NOVOS/TIPO_CONTATO_1.PNG/>
	<br>
	<br>
#### 9.3	CONSULTAS QUE USAM OPERADORES LÓGICOS, ARITMÉTICOS E TABELAS OU CAMPOS RENOMEADOS (Mínimo 11)
    a) Criar 5 consultas que envolvam os operadores lógicos AND, OR e Not<br>

SELECT *FROM PESSOA<br>
	WHERE SEXO = 'Feminino' and NOME ='Adriana'<br>
<img src = https://github.com/carroBD/trab01/blob/master/NOVOS%20OPERADORES%20LOGICOS/FEMININO%20AND%20ADRIANA.PNG/>
	<br><br>
SELECT *FROM MODELO<br>
	WHERE ANO_VEICULO = 2014 OR COR = 'cinza' <br>
<img src = https://github.com/carroBD/trab01/blob/master/NOVOS%20OPERADORES%20LOGICOS/ANO%202014%20OU%20CINZA.PNG/>
	<br><br>
SELECT *FROM MECANICO
	WHERE ESPECIALIZACAO = 'Borracharia' OR CNPJ = '56835725000154'<br>
<img src = https://github.com/carroBD/trab01/blob/master/NOVOS%20OPERADORES%20LOGICOS/BORRACHARIA%20OR%20CNPJ.PNG/>
	<br><br>
SELECT *FROM CONTATO<br>
	WHERE FK_PESSOA_ID_PESSOA = 10 OR CONTATO = '33864931'<br>
<img src = https://github.com/carroBD/trab01/blob/master/NOVOS%20OPERADORES%20LOGICOS/ID%20OU%20CONTATO.PNG/>
	<br>
	<br>
SELECT *FROM GERAM<bf>
	WHERE ESTADO_PECA = 0 OR FK_SENSORES_ID_SENSOR = 5 LIMIT 10'<br>
<img src = https://github.com/carroBD/trab01/blob/master/NOVOS%20OPERADORES%20LOGICOS/ID%20OU%20ESTADO%20PECA%200.PNG/>
	<br>
	<br>
	
    b) Criar no mínimo 3 consultas com operadores aritméticos 
    c) Criar no mínimo 3 consultas com operação de renomear nomes de campos ou tabelas
ALTER TABLE TIPO_CONTATO
	RENAME COLUMN TIPO_CONTATO TO  TIPOS_CONTATOS<br>
	ANTES: <br>
<img src = https://github.com/carroBD/trab01/blob/master/NOVOS%20UPDATES/TIPOS%20CONTATO%20ANTES.PNG/><br>
	DEPOIS: <br>
<img src = https://github.com/carroBD/trab01/blob/master/NOVOS%20UPDATES/TIPOS%20CONTATO%20DEPOIS.PNG/><br>
	<br>
	<br>
ALTER TABLE CONTATO<br>
RENAME COLUMN CONTATO TO CONTATOS<br>
	ANTES: <br>
<img src = https://github.com/carroBD/trab01/blob/master/ALTER%20TABLES/CONTATO%20ANTES.PNG/><br>
	DEPOIS: <br>
<img src = https://github.com/carroBD/trab01/blob/master/ALTER%20TABLES/CONTATO%20DEPOIS.PNG/><br>
	<br>
	<br>
ALTER TABLE MARCA<br>
RENAME COLUMN MARCA TO MARCASbr>
	ANTES: <br>
<img src = https://github.com/carroBD/trab01/blob/master/NOVOS%20UPDATES/MARCA%20ANTES.PNG/><br>
	DEPOIS: <br>
<img src = https://github.com/carroBD/trab01/blob/master/NOVOS%20UPDATES/MARCA%20DEPOIS.PNG/><br>
	<br>
	<br>
    
#### 9.4	CONSULTAS QUE USAM OPERADORES LIKE E DATAS (Mínimo 12) <br>
    a) Criar outras 5 consultas que envolvam like ou ilike
<br>
SELECT *FROM MODELO<br>
	WHERE COR LIKE 'P%';<br>
<img src = https://github.com/carroBD/trab01/blob/master/NOVO%20LIKE/MODELO%20COR%20LIKE%20P.PNG/><br>
<br>
<br>

SELECT *FROM MODELO<br>
	WHERE MODELO_VEICULO like 'C%';<br>
<img src = https://github.com/carroBD/trab01/blob/master/NOVO%20LIKE/MODELO_VEICULO%20LIKE%20C.PNG/>
<br>
<br>

SELECT *FROM PESSOA<br>
	WHERE NOME LIKE 'A%';<br>
<img src = https://github.com/carroBD/trab01/blob/master/NOVO%20LIKE/NOME%20LIKE%20A.PNG/>
<br>
<br>

SELECT *FROM PESSOA<br>
	WHERE NOME NOT ILIKE '%a%';<br>
<img src = https://github.com/carroBD/trab01/blob/master/NOVO%20LIKE/NOME%20NOT%20LIKE%20A.PNG/>
<br>
<br>

SELECT *FROM MARCA<br>
	WHERE MARCAS_VEICULOS ILIKE '%Y%';<br>
<img src = https://github.com/carroBD/trab01/blob/master/NOVO%20LIKE/NOME%20ILIKE%20Y.PNG/><br>
<br>
<br>
	b) Criar uma consulta para cada tipo de função data apresentada.<br>
SELECT *FROM CONTRATA<br>
	WHERE DATA_CONTRATA > '2018-07-15';<br>
<img src = https://github.com/carroBD/trab01/blob/master/NOVO%20DATA/CONTRATA%2020180715.PNG/>
<br>
<br>

SELECT NOME, date_part('year',age(data_nascimento)) FROM PESSOA<br>
	WHERE date_part('year',age(data_nascimento))>40;<br>
<img src = https://github.com/carroBD/trab01/blob/master/NOVO%20DATA/ANIVERSARIO%2040.PNG/>
<br>
<br>

#### 9.5	ATUALIZAÇÃO E EXCLUSÃO DE DADOS (Mínimo 6)<br>
UPDATE MODELO SET COR = 'branco'<br>
	WHERE MODELO_VEICULO = 'i3'<br>
	ANTES: <br>
	<img src = https://github.com/carroBD/trab01/blob/master/ATT%20E%20EXCLUSAO/I3%20ANTES.PNG/>
	DEPOIS: <br>
	<img src = hhttps://github.com/carroBD/trab01/blob/master/ATT%20E%20EXCLUSAO/I3%20DEPOIS.PNG/>
<br>
<br>
UPDATE PESSOA SET DATA_NASCIMENTO = '1999-03-29'<br>
	WHERE NOME = 'Carlos' and CNH = 'E'<br>
	ANTES: <br>
<img src = https://github.com/carroBD/trab01/blob/master/ATT%20E%20EXCLUSAO/CARLOS%20ANTES.PNG/><br>
	DEPOIS: <br>
<img src = https://github.com/carroBD/trab01/blob/master/ATT%20E%20EXCLUSAO/CARLOS%20DEPOIS.PNG/>	
<br>
<br>
UPDATE CONTRATA SET HORA_CONTRATA = '09:43:50'<br>
	WHERE HORA_CONTRATA = '09:40:00';;<br>
	ANTES: <br>
<img src = https://github.com/carroBD/trab01/blob/master/ATT%20E%20EXCLUSAO/CONTRATA%20ANTES.PNG/><br>
	DEPOIS: <br>
<img src = https://github.com/carroBD/trab01/blob/master/ATT%20E%20EXCLUSAO/CONTATO%20DEPOIS.PNG/>
<br>
<br>
UPDATE CONTATO <br>
	SET CONTATO = '999999999' WHERE ID_CONTATO = 3;<br>
	ANTES: <br>
<img src = https://github.com/carroBD/trab01/blob/master/ATT%20E%20EXCLUSAO/CONTATO%20ANTES.PNG/><br>
	DEPOIS: <br>
<img src = https://github.com/carroBD/trab01/blob/master/ATT%20E%20EXCLUSAO/CONTATO%20DEPOIS.PNG/>
<br>
<br>

UPDATE PESSOA<br>
	SET ESPECIALIZACAO = 'Borracharia'<br>
	WHERE ID_PESSOA >= 1 AND id_pessoa<=22 AND PESSOA TIPO =1;<br>
	ANTES: <br>
<img src = https://github.com/carroBD/trab01/blob/master/ATT%20E%20EXCLUSAO/ESPECILIZACAO%20ANTES%201.PNG/><br>
	DEPOIS: <br>
<img src = https://github.com/carroBD/trab01/blob/master/ATT%20E%20EXCLUSAO/ESPECILIZACAO%20DEPOIS%201.PNG/>
<br>
<br>

UPDATE PESSOA<br>
	SET ESPECIALIZACAO = 'Eletrica'<br>
	WHERE ID_PESSOA >= 23 AND id_pessoa<=36 AND PESSOA TIPO =1;<br>
	ANTES: <br>
<img src = https://github.com/carroBD/trab01/blob/master/ATT%20E%20EXCLUSAO/ESPECILIZACAO%20ANTES%202.PNG/><br>
	DEPOIS: <br>
<img src = https://github.com/carroBD/trab01/blob/master/ATT%20E%20EXCLUSAO/ESPECILIZACAO%20DEPOIS%202.PNG/>
<br>
<br>

UPDATE PESSOA<br>
	SET ESPECIALIZACAO = 'Mecânica'<br>
	WHERE ID_PESSOA >= 37 AND id_pessoa<=49 AND PESSOA TIPO =1;<br>
	ANTES: <br>
<img src = https://github.com/carroBD/trab01/blob/master/ATT%20E%20EXCLUSAO/ESPECILIZACAO%20ANTES%203.PNG/><br>
	DEPOIS: <br>
<img src = https://github.com/carroBD/trab01/blob/master/ATT%20E%20EXCLUSAO/ESPECILIZACAO%20DEPOIS%203.PNG/>
<br>
<br>

UPDATE PESSOA<br>
	SET ESPECIALIZACAO = 'Lanterneiro'<br>
	WHERE ID_PESSOA >= 54 AND id_pessoa<=72 AND PESSOA TIPO =1;<br>
	ANTES: <br>
<img src = https://github.com/carroBD/trab01/blob/master/ATT%20E%20EXCLUSAO/ESPECILIZACAO%20ANTES%204.PNG/><br>
	DEPOIS: <br>
<img src = https://github.com/carroBD/trab01/blob/master/ATT%20E%20EXCLUSAO/ESPECILIZACAO%20DEPOIS%204.PNG/>
<br>
<br>

>## Marco de Entrega 04 em: (18/10/2017)<br>

#### 9.6	CONSULTAS COM JUNÇÃO E ORDENAÇÃO (Mínimo 6)<br>
        a) Uma junção que envolva todas as tabelas possuindo no mínimo 3 registros no resultado
SELECT nome, contatos, tipos_contatos, placa, modelo_veiculo, marcas, categoria, nome_sensor, tipo_sensor,estado_peca, hora_analise, data_contrata from pessoa<br>
	inner join veiculo on (pessoa.id_pessoa = veiculo.fk_pessoa_id_pessoa)
	inner join modelo on (modelo.id_modelo = veiculo.fk_modelo_id_modelo)
	inner join marca on (modelo.fk_marca_id_marca = marca.id_marca)
	inner join categoria on (veiculo.fk_categoria_id_categoria = categoria.id_categoria)
	inner join contato on (contato.fk_pessoa_id_pessoa = pessoa.id_pessoa)
	inner join tipo_contato on (contato.fk_tipo_contato_id_tipo_contato = tipo_contato.id_tipo_contato)
	inner join sensores on (sensores.fk_veiculo_id_veiculo = veiculo.id_veiculo )
	inner join tipo_sensor on (sensores.fk_tipo_sensor_id_tipo_sensor = tipo_sensor.id_tipo_sensor)
	inner join geram on (geram.fk_sensores_id_sensor = sensores.id_sensor)
	inner join historico on (geram.fk_historico_id_historico = historico.id_historico)
	inner join contrata on (contrata.fk_pessoa_id_pessoa = pessoa.id_pessoa);<br>
<img src = https://github.com/carroBD/trab01/blob/master/INNER%20JOINS/INNER%20JOIN%20TODAS%20TODAS%20AS%20TAB.PNG/><br>
<img src = https://github.com/carroBD/trab01/blob/master/INNER%20JOINS/INNER%20JOIN%20TODAS%20TODAS%20AS%20TAB%202.PNG/><br>
<br>
<br>
	b) Outras junções que o grupo considere como sendo as de principal importância para o trabalho<br>
	JUNÇÃO PARA MOSTRAR A SITUAÇÃO ACERCA DOS CARROS DOS CLIENTES.<br>
	CÓDIGO: SELECT NOME, PLACA, NOME_SENSOR,ESTADO_PECA FROM PESSOA<br>
	INNER JOIN VEICULO ON (PESSOA.ID_PESSOA = VEICULO.FK_PESSOA_ID_PESSOA)
	INNER JOIN SENSORES ON (VEICULO.ID_VEICULO = SENSORES.FK_VEICULO_ID_VEICULO)
	INNER JOIN GERAM ON (SENSORES.ID_SENSOR = GERAM.FK_SENSORES_ID_SENSOR);<br>
<img src=https://github.com/carroBD/trab01/blob/master/INNER%20JOINS/INNER%20JOIN%20NOME%20PLACA%20SENSOR%20E%20ESTADO%20PECA%201.PNG/><br>
<img src=https://github.com/carroBD/trab01/blob/master/INNER%20JOINS/INNER%20JOIN%20NOME%20PLACA%20SENSOR%20E%20ESTADO%20PECA%202.PNG/><br>
<br>
	JUNÇÃO PARA MOSTRAR OS MODELOS COM PEÇAS COM DEFEITO<br>
	CÓDIGO: SELECT MODELO_VEICULO, ESTADO_PECA FROM VEICULO<br>
	INNER JOIN MODELO ON (VEICULO.FK_MODELO_ID_MODELO = MODELO.ID_MODELO)
	INNER JOIN SENSORES ON (VEICULO.ID_VEICULO = SENSORES.FK_VEICULO_ID_VEICULO)
	INNER JOIN GERAM ON (SENSORES.ID_SENSOR = GERAM.FK_SENSORES_ID_SENSOR)
	WHERE ESTADO_PECA = 1;<br>
<img src=https://github.com/carroBD/trab01/blob/master/INNER%20JOINS/INNER%20JOIN%20MODELO%20E%20PE%C3%87AS%20COM%20DEFEITO.PNG/><br>
<br>
<br>
	JUNÇÃO PARA MOSTRAR AS CONTRATAÇÕES FEITAS PELOS CLIENTES.<br>
	CÓDIGO: SELECT NOME, HORA_CONTRATA, DATA_CONTRATA FROM PESSOA
	INNER JOIN CONTRATA ON (PESSOA.ID_PESSOA = CONTRATA.FK_PESSOA_ID_PESSOA)
	WHERE PESSOA_TIPO = 0;<br>
	<img src=https://github.com/carroBD/trab01/blob/master/INNER%20JOINS/INNER%20JOIN%20CLIENTE%20CONTRATA.PNG/><br>
	<img src=https://github.com/carroBD/trab01/blob/master/INNER%20JOINS/INNER%20JOIN%20CLIENTE%20CONTRATA%202.PNG/><br>

<br>
<br>
	JUNÇÃO PARA MOSTRAR AS CORES DOS CARROS DO SEXO FEMININO.<br>
	CÓDIGO: SELECT NOME, PLACA, COR FROM PESSOA<br>
	INNER JOIN VEICULO ON (PESSOA.ID_PESSOA = VEICULO.FK_PESSOA_ID_PESSOA)<br>
	INNER JOIN MODELO ON (VEICULO.FK_MODELO_ID_MODELO = MODELO.ID_MODELO)<br>
	WHERE SEXO = 'Feminino'<br>
	<img src = https://github.com/carroBD/trab01/blob/master/INNER%20JOINS/COR%20CARRO%20POR%20SEXO.PNG/><br>
	<br>
	<br>
	JUNÇÃO PARA MOSTRAR AS DATAS DE ANÁLISES ACIMA DE UMA DETERMINADA DATA.<br>
	SELECT PLACA, DATA_ANALISE FROM VEICULO<br>
	INNER JOIN SENSORES ON (VEICULO.ID_VEICULO = SENSORES.FK_VEICULO_ID_VEICULO)<br>
	INNER JOIN GERAM ON (SENSORES.ID_SENSOR = GERAM.FK_SENSORES_ID_SENSOR)<br>
	INNER JOIN HISTORICO ON (GERAM.FK_HISTORICO_ID_HISTORICO = HISTORICO.ID_HISTORICO)<br>
	WHERE DATA_ANALISE > '03-10-2018'<br>
	<img src = https://github.com/carroBD/trab01/blob/master/INNER%20JOINS/INNER%20JOIN%20DATA%20MAIOR.PNG/><br>
	<br>
	<br>

	
#### 9.7	CONSULTAS COM GROUP BY E FUNÇÕES DE AGRUPAMENTO (Mínimo 6)<br>
CÓDIGO: SELECT SEXO, count(*)FROM PESSOA <br>
	GROUP BY SEXO;<br>
	<img src=https://github.com/carroBD/trab01/blob/master/GROUP%20BY/GROUP%20BY%20SEXO.PNG/><br>
	<br>
	<br>
CÓDIGO: SELECT COR, count(*) FROM MODELO<br>
	GROUP BY COR;<br>
	<img src = https://github.com/carroBD/trab01/blob/master/GROUP%20BY/GROUP%20BY%20COR.PNG/><br>
	<br>
	<br>
CÓDIGO: SELECT DESCRICAO, COUNT(DESCRICAO) AS QUEBRAS FROM SENSORES<br>
	INNER JOIN GERAM ON (SENSORES.ID_SENSOR = GERAM.FK_SENSORES_ID_SENSOR)<br>
	WHERE ESTADO_PECA = 1 GROUP BY DESCRICAO<br>
	<img src = https://github.com/carroBD/trab01/blob/master/GROUP%20BY/GROUP%20BY%20PECAS%20QUEBRADAS.PNG/><br>
	<br>
	<br>
CÓDIGO: SELECT NOME, ESPECIALIZACAO,COUNT(NOME) AS CHAMADAS FROM PESSOA<br>
	INNER JOIN CONTRATA ON (PESSOA.ID_PESSOA = CONTRATA.FK_PESSOA_ID_MECANICO)<br>
	GROUP BY NOME, ESPECIALIZACAO<br> WHERE ESTADO_PECA = 1 GROUP BY DESCRICAO<br>
	<img src = https://github.com/carroBD/trab01/blob/master/GROUP%20BY/GROUP%20BY%20CHAMADA%20MECANICO.PNG/><br>
	<br>
	<br>
CÓDIGO: SELECT MODELO_VEICULO, ESTADO_PECA, count(*) AS SOMA FROM VEICULO<br>
	INNER JOIN MODELO ON (VEICULO.FK_MODELO_ID_MODELO = MODELO.ID_MODELO)<br>
	INNER JOIN SENSORES ON (VEICULO.ID_VEICULO = SENSORES.FK_VEICULO_ID_VEICULO)<br>
	INNER JOIN GERAM ON (SENSORES.ID_SENSOR = GERAM.FK_SENSORES_ID_SENSOR)<br>
		WHERE ESTADO_PECA = 1 GROUP BY MODELO_VEICULO, ESTADO_PECA<br>
	<img src = https://github.com/carroBD/trab01/blob/master/GROUP%20BY/GROUP%20BY%20MODELOS%20DEFEITOS.PNG/><br>
	<br>
	<br>
	
CÓDIGO: SELECT NOME, date_part('year',age(data_nascimento)), ESTADO_PECA, count(ESTADO_PECA) FROM PESSOA<br>
	iNNER JOIN VEICULO ON (PESSOA.ID_PESSOA = VEICULO.FK_PESSOA_ID_PESSOA)<br>
	INNER JOIN SENSORES ON (VEICULO.ID_VEICULO = SENSORES.FK_VEICULO_ID_VEICULO)<br>
	INNER JOIN GERAM ON (SENSORES.ID_SENSOR = GERAM.FK_SENSORES_ID_SENSOR)<br>
	WHERE ESTADO_PECA = 1 GROUP BY NOME, DATE_PART,ESTADO_PECA; <br>
	<img src = https://github.com/carroBD/trab01/blob/master/GROUP%20BY/GROUP%20BY%20IDADE%20X%20PECA%20QUEBRADA.PNG/><br>
	<br>
	<br>
	
#### 9.8	CONSULTAS COM LEFT E RIGHT JOIN (Mínimo 4)<br>
SELECT CONTATO.CONTATOS, PESSOA.NOME, VEICULO.PLACA FROM CONTATO<br>
	LEFT JOIN PESSOA ON (PESSOA.ID_PESSOA = CONTATO.FK_PESSOA_ID_PESSOA)<br>
	RIGHT OUTER JOIN VEICULO ON VEICULO.FK_PESSOA_ID_PESSOA = PESSOA.ID_PESSOA<br>
	<img src = https://github.com/carroBD/trab01/blob/master/LEFT%20E%20RIGHT%20JOIN/LEFT%201.PNG/><br>
	<img src = https://github.com/carroBD/trab01/blob/master/LEFT%20E%20RIGHT%20JOIN/LEFT%202.PNG/><br>
	<br>
	<br>
SELECT PESSOA.NOME AS MOTORISTA,CONTRATA.HORA_CONTRATA, CONTRATA.DATA_CONTRATA <br>
	FROM PESSOA LEFT JOIN CONTRATA ON PESSOA.ID_PESSOA = CONTRATA.FK_PESSOA_ID_PESSOA<br>
	<img src = https://github.com/carroBD/trab01/blob/master/LEFT%20E%20RIGHT%20JOIN/LEFT%2021.PNG/><br>
	<img src = https://github.com/carroBD/trab01/blob/master/LEFT%20E%20RIGHT%20JOIN/LEFT%2022.PNG/><br>
	<img src = https://github.com/carroBD/trab01/blob/master/LEFT%20E%20RIGHT%20JOIN/LEFT%2023.PNG/><br>
	<br>
	<br>
SELECT VEICULO.PLACA, MARCA.MARCAS, MODELO.MODELO_VEICULO, MODELO.COR, MODELO.ANO_VEICULO<br>
	FROM VEICULO LEFT JOIN MODELO ON MODELO.ID_MODELO = VEICULO.FK_MODELO_ID_MODELO<br>
	LEFT JOIN MARCA ON MODELO.FK_MARCA_ID_MARCA = MARCA.ID_MARCA<br>
	<img src = https://github.com/carroBD/trab01/blob/master/LEFT%20E%20RIGHT%20JOIN/LEFT%2031.PNG/><br>
	<img src = https://github.com/carroBD/trab01/blob/master/LEFT%20E%20RIGHT%20JOIN/LEFT%2032.PNG/><br>
	<br>
	<br>
SELECT SENSORES.NOME_SENSOR, TIPO_SENSOR.TIPO_SENSOR, GERAM.ESTADO_PECA, HISTORICO.DATA_ANALISE, HISTORICO.HORA_ANALISE<br>
	FROM SENSORES LEFT JOIN TIPO_SENSOR ON SENSORES.FK_TIPO_SENSOR_ID_TIPO_SENSOR = TIPO_SENSOR.ID_TIPO_SENSOR<br>
	RIGHT JOIN GERAM ON GERAM.FK_SENSORES_ID_SENSOR = SENSORES.ID_SENSOR<br>
	LEFT JOIN HISTORICO ON GERAM.FK_HISTORICO_ID_HISTORICO = HISTORICO.ID_HISTORICO WHERE ESTADO_PECA = 1<br>
	<img src = https://github.com/carroBD/trab01/blob/master/LEFT%20E%20RIGHT%20JOIN/LEFT%204.PNG/><br>
	<br>
	<br>


	
#### 9.9	CONSULTAS COM SELF JOIN E VIEW (Mínimo 6)<br>
        a) Uma junção que envolva Self Join
        b) Outras junções com views que o grupo considere como sendo de relevante importância para o trabalho
CREATE VIEW VIEW_MECANICOS AS SELECT * FROM PESSOA <br>
	WHERE PESSOA_TIPO = 1 LIMIT = 5;<br>
<img src = https://github.com/carroBD/trab01/blob/master/VIEWS/VIEW%20PESSOA%20TIPO%201.PNG/><br>
<br>
<br>
CREATE VIEW VIEW_MOTORISTAS AS SELECT * FROM PESSOA <br>
WHERE PESSOA_TIPO = 0 LIMIT 5;<br>
<img src = https://github.com/carroBD/trab01/blob/master/VIEWS/VIEW%20PESSOA%20TIPO%200.PNG/><br>
<br>
<br>
CREATE VIEW VIEW_MOTORISTASXCARROS AS SELECT VEICULO.PLACA, PESSOA.NOME<br>
	FROM PESSOA INNER JOIN VEICULO ON (PESSOA.ID_PESSOA = VEICULO.FK_PESSOA_ID_PESSOA) LIMIT 5;<br>
	<img src = https://github.com/carroBD/trab01/blob/master/VIEWS/MOTORISTASXCARROS.PNG/><br>
	<br>
	<br>

CREATE VIEW VIEW_MOTOS AS SELECT VEICULO.PLACA, CATEGORIA.CATEGORIA
	FROM VEICULO LEFT JOIN CATEGORIA ON (VEICULO.FK_CATEGORIA_ID_CATEGORIA = ID_CATEGORIA AND ID_CATEGORIA = 2) 
LIMIT 5;<br>
	<img src = https://github.com/carroBD/trab01/blob/master/VIEWS/VIEW%20MOTOS.PNG/><br>
	<br>
	<br>
CREATE VIEW VIEW_CONTATOS AS SELECT PESSOA.NOME, CONTATO.CONTATOS FROM PESSOA<br>
	LEFT JOIN CONTATO ON (PESSOA.ID_PESSOA = CONTATO.FK_PESSOA_ID_PESSOA) LIMIT 5;<br>
	<img src = https://github.com/carroBD/trab01/blob/master/VIEWS/VIEW%20CONTATOS.PNG/><br>
	<br>
	<br>
CREATE VIEW VIEW_SENSORES AS SELECT * FROM SENSORES LIMIT 10;<br>
<img src = https://github.com/carroBD/trab01/blob/master/VIEWS/VIEW%20SENSORES.PNG/><br>
	<br>
	<br>



#### 9.10	SUBCONSULTAS (Mínimo 3)<br>
SELECT DATA_NASCIMENTO, NOME,DATE_PART('YEAR',AGE(DATA_NASCIMENTO)) AS IDADE FROM PESSOA<br>
WHERE DATA_NASCIMENTO = (SELECT MIN(DATA_NASCIMENTO) FROM PESSOA)<br>
	<img src = https://github.com/carroBD/trab01/blob/master/SUBCONSULTA/SUBCONSULTA%201.PNG/><br>
	<br>
	<br>
	
SELECT DATA_NASCIMENTO, NOME,DATE_PART('YEAR',AGE(DATA_NASCIMENTO)) AS IDADE FROM PESSOA<br>
WHERE DATA_NASCIMENTO = (SELECT MAX(DATA_NASCIMENTO) FROM PESSOA)<br>
	<img src = https://github.com/carroBD/trab01/blob/master/SUBCONSULTA/SUBCONSULTA%202.PNG/><br>
	<br>
	<br>
SELECT HISTORICO.DATA_ANALISE, HISTORICO.HORA_ANALISE, GERAM.ESTADO_PECA<br>
FROM HISTORICO INNER JOIN GERAMON GERAM.FK_HISTORICO_ID_HISTORICO = HISTORICO.ID_HISTORICO<br>
INNER JOIN SENSORES<br>
ON GERAM.FK_SENSORES_ID_SENSOR = SENSORES.ID_SENSOR<br>
WHERE DATA_ANALISE = (SELECT MIN(DATA_ANALISE) FROM HISTORICO)<br>
	<img src = https://github.com/carroBD/trab01/blob/master/SUBCONSULTA/SUBCONSULTA%203.PNG/><br>
	<br>
	<br>


### 10	ATUALIZAÇÃO DA DOCUMENTAÇÃO DOS SLIDES PARA APRESENTAÇAO FINAL (Mínimo 6 e Máximo 10)<br>
LINK DOS SLIDES: http://prezi.com/j-kwizfyfqhh/?utm_campaign=share&utm_medium=copy&rc=ex0share<br>

### 11 Backup completo do banco de dados postgres 
<a href="https://github.com/carroBD/trab01/blob/master/carro_BACKUPFINAL">Arquivo de backup</a><br>
	Grupo de teste: Controle de Frequência[Brunna Dalzini de Oliveira, Daniela Salomão Santa Clara, Leonir dos Reis Alves, Mayannara Trindade Carvalho]

### 12	TUTORIAL COMPLETO DE PASSOS PARA RESTAURACAO DO BANCO E EXECUCAO DE PROCEDIMENTOS ENVOLVIDOS NO TRABALHO PARA OBTENÇÃO DOS RESULTADOS<br>

Para começar, primeiramente, escolha ou crie um banco de dados, clique com o botão direito sobre o mesmo e clique em "Restore".<br>
Deverá aparecer algo mais ou menos assim:<br>
<img src = https://github.com/carroBD/trab01/blob/master/TUTORIAL/passo1.PNG/><br>
Feito isso, aparecerá essa tela:<br>
<img src = https://github.com/carroBD/trab01/blob/master/TUTORIAL/passo2.PNG/><br>
Clique nos três pontos indicados pela região em vermelho.<br>
Após, navegue até onde está salvo o backup, no nosso caso, o arquivo "carro_BACKUPFINAL".<br>
Selecione o arquivo: <br>
<img src = https://github.com/carroBD/trab01/blob/master/TUTORIAL/passo3.PNG/><br>
E clique no botão azul escrito "Select"<br>
<img src = https://github.com/carroBD/trab01/blob/master/TUTORIAL/passo4.PNG/><br>
Para finalizar, confira se em Format está escrito "Custom or tar" e se o caminho e o arquivo estão corretos.<br>
Caso esteja tudo certo, clique em "Restore".<br>
<img src = https://github.com/carroBD/trab01/blob/master/TUTORIAL/passo5.PNG/><br>
Se seguiu todos esses passos corretamente, você deve receber uma mensagem indicando que a restauração foi um sucesso, como essa:<br>
<img src = https://github.com/carroBD/trab01/blob/master/TUTORIAL/passo6.PNG/><br>
Pronto! Agora seu banco de dados está pronto para uso!<br>
        
### 13   DIFICULDADES ENCONTRADAS PELO GRUPO<br>
Dificuldades encontradas pelo grupo:<br>
- Desistência de integrantes: Metade do grupo ficou ausente do trabalho por motivos pessoais e/ou desconhecidos.<br>
- Self Join: O grupo não conseguiu identificar essa situação no trabalho.<br>
- Objetivo do sistema: a principio, a ideia era complexa. Modificações tiveram que ser feitas para simplificação e execução do trabalho<br>
- Operações aritméticas: O grupo deve dificuldades pra encontrar e realizá-las<br>
>## Marco de Entrega Final em: (08/11/2018)<br>

        
### 14  FORMATACAO NO GIT: https://help.github.com/articles/basic-writing-and-formatting-syntax/
<comentario no git>
    
##### About Formatting
    https://help.github.com/articles/about-writing-and-formatting-on-github/
    
##### Basic Formatting in Git
    
    https://help.github.com/articles/basic-writing-and-formatting-syntax/#referencing-issues-and-pull-requests
    
    
##### Working with advanced formatting
    https://help.github.com/articles/working-with-advanced-formatting/
#### Mastering Markdown
    https://guides.github.com/features/mastering-markdown/



    

    
### OBSERVAÇÕES IMPORTANTES

#### Todos os arquivos que fazem parte do projeto (Imagens, pdfs, arquivos fonte, etc..), devem estar presentes no GIT. Os arquivos do projeto vigente não devem ser armazenados em quaisquer outras plataformas.
1. Caso existam arquivos com conteúdos sigilosos, comunicar o professor que definirá em conjunto com o grupo a melhor forma de armazenamento do arquivo.

#### Todos os grupos deverão fazer Fork deste repositório e dar permissões administrativas ao usuário do git "profmoisesomena", para acompanhamento do trabalho.

#### Os usuários criados no GIT devem possuir o nome de identificação do aluno (não serão aceitos nomes como Eu123, meuprojeto, pro456, etc). Em caso de dúvida comunicar o professor.


Link para BrModelo:<br>
http://www.sis4.com/brModelo/download.html
<br>


Link para curso de GIT<br>
![https://www.youtube.com/curso_git](https://www.youtube.com/playlist?list=PLo7sFyCeiGUdIyEmHdfbuD2eR4XPDqnN2?raw=true "Title")


