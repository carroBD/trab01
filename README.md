# TRABALHO 01:  Smart Car - Carro inteligente.
Trabalho desenvolvido durante a disciplina de BD1.

# Sumário
A editar
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
Acerca da imprudência, estão diversos fatores, principalmente a não revisão veicular e falhas mecânicas dos componentes veiculares, provenientes do descaso dos motoristas com seus veículos. E é em cima desse problema que o sistema “Smart Car” visa colaborar. O sistema tem como finalidade gerenciar os componentes mecânicos do carro (giro do motor, pistão, pneus, precisão dos controles) a fim de gerar dados sobre esses componentes e prever possíveis falhas, evitando os acidentes por falhas mecânicas nas estradas. O sistema visa atuar também em cima do dinamismo acerca do tempo da sociedade contemporânea , impactando no ganho de tempo no cotidiano do usuário, possibilitando, por exemplo, que o usuário do sistema, ao ser notificado de um possível risco de falha de um componente, possa agendar diretamente, com um mecânico de sua escolha, uma revisão ou troca do componente, agilizando sua rotina e trabalho de vistoria do mecânico, evitando perda de tempo para ambas as partes. Para isso, o sistema contará com sensores de controle, gerando dados sobre os componentes, e possibilitará o cadastro do carro e de mecânicos especializados escolhidos e cadastrados pelo cliente para contato. O sistema notificará com um tempo satisfatório uma possível falha de algum componente e deverá armazenar esses dados de falhas em bancos de dados para possíveis novas análises.</div> 

### 3.MINI-MUNDO<br>
<p align="justify">O sistema “Smart Car” proposto tem por objetivo a inspeção e análise  veicular, a fim de gerar análises dos componentes do veículo. Acerca das inspeções, cada carro contará com sensores, cada sensor é associado a um, e somente um, componente do carro. O carro poderá contar com mais de um sensor e cada carro terá um motorista a ele associado. Cada sensor terá seu nome de identificação, finalidade e identificação associando em qual carro está inserido. Será necessário um cadastro do cliente com nome e cpf, para identificação. No que tange ao carro, será necessário armazenar todas as informações sobre o veículo, como chassi, placa, ano, modelo, e seus respectivos componentes instalados. Cada carro poderá ter um, e somente um, motorista associado. O sistema deve ser capaz de notificar o usuário de forma simples e clara, a fim de especificar a possível falha de algum componente, através de um esquema de cores simplificado, a situação do componente do carro. O sistema deve realizar cadastro de mecânicos, escolhidos pelo usuário, a fim de estabelecer um contato entre os dois agentes. Deverá permitir também um contato de forma simples e direta, com a possibilidade de cadastro de mais de um mecânico por cliente. O sistema não ficará responsável pelo controle de peças por parte do mecânico, o mesmo apenas estabelecerá um contato entre cliente-mecânico, a fim de ambos chegaram a um consenso para possível revisão/troca do componente. O sistema não fornecerá dados do componentes instalados no carro do motorista, por questão de privacidade e risco de possíveis fraudes nos componentes ou na hora do serviço prestado. No momento do contato, será informado apenas a data da possível falha e respectivo componente que poderá ocorrer a falha. O sistema contará com diferenciação no cadastro entre ser cliente ou mecânico.a fim de proporcionar telas diferentes para ambos. Na tela do mecânico contará apenas os clientes que o adicionaram ao usar o programa. Será necessário captar os dados como Nome, CPF, nome da oficina, CNPJ e demais informações a fim de prover controle e segurança para os clientes. Com  Já a tela do motorista contará com dados dos sensores, sensores instalados, carros cadastrados, mecânicos cadastrados e área para contato com o mecânico que assim desejar.</div> 



### 4.RASCUNHOS BÁSICOS DA INTERFACE (MOCKUPS)<br>
<p align="justify"><b>Tela 1: Tela de login do aplicativo. </b><br>
    <img src=https://github.com/carroBD/trab01/blob/master/Imagens/TELA%20DE%20LOGIN.PNG/> <br>
Essa é a tela inicial, onde mecânicos e motoristas farão o login para iniciar suas ações no app. <br>
<br><b>Tela 2: Tela após login de um usuário tipo Cliente. </b><br>
    <img src=https://github.com/carroBD/trab01/blob/master/Imagens/TELA%20APOS%20O%20LOGIN.PNG/><br>
Essa é a tela pós-login de um usuário tipo cliente, a tela mostrará os carros cadastrados pelos clientes, foto do carro, nome do usuário logado e um botão para inicio da análise e acesso as informações provenientes dos sensores instalados em cada carro.<br>
    <br><b>Tela 3: Tela após seleção do carro e inicio da análise veicular</b><br>
    <img src=https://github.com/carroBD/trab01/blob/master/Imagens/TELA%20APOS%20SELECIONAR%20O%20CARRO%20E%20VER%20SITUA%C3%87%C3%83O.PNG/><br>
    Essa é a tela onde serão mostradas as informações acerca de cada componente do carro, baseado nas análises geradas pelos sensores. O app fará uma identificação visual simples, através de 3 indicadores de cor: Verde para sem previsãod e falha do componente; Amarelho para previsão de falha em um mês; Vermelho para componente com defeito. O cliente poderá Clicar sobre cada componente e ter um acesso mais detalhado da situação, como será mostrado a seguir.<br>
    <br><b>Tela 4: Tela para detalhamento da peça do carro</b><br>
     <img src=https://github.com/carroBD/trab01/blob/master/Imagens/TELA%20DE%20DETALHAMENTO%20DA%20PE%C3%87A%20DO%20MOTORISTA.PNG/><br>
    Nessa tela o motorista poderá conferir detalhes sopre uma peça especifica de sua escolha. A partir dessa tela também será pssível acionar o mecânico.<br>
    <br><b>Tela 5: Tela para acionar mecânico</b><br>
    <img src=https://github.com/carroBD/trab01/blob/master/Imagens/TELA%20DE%20CHAMADA%20DO%20MECANICO.PNG/><br>
    Nessa tela o cliente poderá ver os dados do mecânico escolhido e poderá enviar os dados sobre o componente de uma determinada peça para possível análise do mecânico ou agendamento de uma revisão.<br>
    <br><b>Tela 6: Tela pós-login de um usuário tipo mecânico</b><br>
    <img src=https://github.com/carroBD/trab01/blob/master/Imagens/TELA%20APOS%20LOGIN%20DO%20MECANICO.PNG/><br>
    Nessa tela, após a diferenciação do login do tipo de cliente (mecânico), ele terá acesso a botões que mostrarão os clientes da sua base de dados, chamadas em espera de clientes e alteração no seu perfil.<br>
    <br><b>Tela 7: Tela de visualização de chamadas em aberto do usuário tipo mecânico</b><br>
    <img src=https://github.com/carroBD/trab01/blob/master/Imagens/TELA%20CHAMADAS%20PRO%20MECANICO.PNG/><br>
    Essa tela contém dados sobre as chamadas feitas por usuários do tipo motoristas para um determinado usuário do tipo mecânico, solicitado algum tipo de serviço.<br>
    <br><b>Tela 8: Tela de visualização da base de dados de clientes do usuário tipo mecânico</b><br>
    <img src= https://github.com/carroBD/trab01/blob/master/Imagens/tela%20de%20informacao%20dos%20clientes%20-%20mecanico.PNG/><br>
    Nessa tela o usuário do tipo mecânico poderá consultar os dados sobre seus clientes existentes em sua base de dados.<br></div>
    
    
    
#### 4.1 QUAIS PERGUNTAS PODEM SER RESPONDIDAS COM O SISTEMA PROPOSTO?
   O sistema poderá contar com uma série de dados acerca de gerarem metadados para novas avaliações, seja sobre o modelo do carro, perfil do motorista ou disponibilidade do mecânico. Assim, sistema proposto servirá para adiquirir e gerar relatórios, como por exemplo os citados abaixo:
   - Relatório geral sobre a situação do carro do cliente
   - Relatório de quais componentes do carro quebram com mais frequência
   - Relatório acerca da quais mecânicos estão mais disponíveis
   - Relatório de quais modelos de carro apresentam mais falhas
   - Relatório de Peça quebrada/Km rodado do modelo de carro.
   - Perfil dos motoristas.

 
#### 4.2 TABELA DE DADOS DO SISTEMA:
<img src=https://github.com/carroBD/trab01/blob/master/Planilha/Planilha%20BD.xlsx/>
<br><b>"Tabela - SmartCar"</b>
Tabela relacionando entidades e componentes existente no sistema e banco de dados.
    
>## Marco de Entrega 01 em: (30/08/2018)<br>

### 5.MODELO CONCEITUAL<br>
        
<img src=https://github.com/carroBD/trab01/blob/master/Imagens/Conceitual_final_4.png/>
    
   
    
        
    
#### 5.1 Validação do Modelo Conceitual
    [Transporte de Carnes]: Rafael dos Anjos, Daniel Comerio,Nicolas Sampaio,Andreas Hermes.
    [Controle de Rotas]: Ana Paula,Italo Vaz,Luma Gonçalvez,Rafael Sampogna.

#### 5.2 DECISÕES DE PROJETO

    ATRIBUTOS
    
    Nome: O campo é simples. Servirá apenas para armazenar o nome do cliente e não para identificá-lo.
    Nome oficina: Campo simples. Este campo armazenará o nome da oficina pertencente ao mecânico, e não servirá para identificá-la.
    CPF: Campo simples e determinante. Servirá para identificar o cliente na lista de clientes.
    CNPJ: Simples e determinante. Com esse dado é possível identificar uma única oficina.
    Carro cliente: Composto e multivalorado.
    Email cliente: Campo simples e multivalorado; É possível um cliente possuir vários emails para contato.
    Telefone cliente: Campo simples e multivalorado. É possível um cliente possuir vários telefones de contato.
    Placa veiculo: Campo simples e determinante. Com a placa é possível especificar o carro procurado.
    Modelo veiculo: Campo simples.
    Endereço cliente: Campo simples e multivalorado, pois é possível um cliente pode possuir endereços diferentes, 
    de casa e trabalho por exemplo.
    Endereço mecânico: Campo simples e multivalorado. É possível uma oficina possuir filiais.


>## Marco de Entrega 02 em: (13/09/2018)<br>

#### 5.3 DESCRIÇÃO DOS DADOS.]
    CLIENTE: TABELA QUE ARMAZENA OS DADOS DOS USUÁRIOS TIPO CLIENTE.
        - Nome: Campo que armazena o NOME de cada uuário dp tipo cliente.
        - CPF: Campo que armazena o número do CPF do usuário do tipo cliente.
        - Email: Campo que armazena o EMAIL do usuário tipo cliente.
        - Telefone: Campo que armazena o TELEFONE do usuário do tipo cliente.
        - carro_cliente: Campo que armazena a marca do carro do cliente.
    
    MECÂNICO: TABELA QUE ARMAZENA OS DADOS DO USUÁRIO TIPO MECÂNICO.
        - CPNJ: Campo que armazena o CNPJ da oficina do usuário do tipo mecânico.
        - NOME_OFICINA: Campo que armazerna o NOME da oficina do usuário tipo mecânico.
        - CPF_cliente: Campo que armazerna o CPF do cliente.
        - NOME: Campo que armazena o nome do usuário do tipo mecânico.
        
    VEÍCULO: TABELA QUE ARMAZENA OS DADOS DO VEÍCULO CADASTRADO POR UM USUÁRIO DO TIPO CLIENTE.
        - Placa_Carro: Campo que armazena a placa de um veículo cadastrado por um usuário do tipo cliente.
        - Id_veiculo: Campo que armazena a ID do veículo.
        - cpf_dono: Campo que armazena o CPF do dono do veiculo.
        
    CATEGORIA_VEÍCULO: TABELA QUE ARMAZENA DADOS SOBRE A CATEGORIA DE TODOS OS CARROS CADASTRADOS NO SISTEMA POR UM USUÁRIO DO TIPO CLIENTE.
        - placa_veiculo: Campo que armazena a placa do carro.
        - Historico defeito: Campo que armazena o historico de defeito do carro.
        - Modelo_vepiculo: Tabela que armazena o modelo do veículo.
        
    SENSOR: Tabela que armazena os dados sobre os sensores instalados no veículo.
   
        - ID_Sensor: Campo que armazena o ID de um sensor.
        - Analise_Peça: Campo que armazena um valor sobre a análise da peça.
        - Peça_sensor: Campo que armazena uma peça de responsabilidade de algum sensor.
        
    DADOS: Tabela que armazena os dados gerados sobre os sensores instalados no veículo.
        - ID Dados: Campo que armazena um id para um tipo de dado:
        - Situação_peça: Campo que armazena um valor sobre a situação da peça.
        - tempo_defeito: Campo que armazena um valor que marca a data de um defeito de uma determinada peça
        - Tipo defeito: Campo que armazena o tipo de defeito detectado por um sensor em uma determinada peça.
        - Previsão_falha: Campo que armazena um valor sobre a precisão de falha de uma determinada peça.
    
    HISTORICO: Tabela que armazena os dados que geram um historico sobre o veiculo.
        -Nome_peça: Campo que armazena o nome referente a peça do veiculo.
        -Sensor_peça: Campo que armazena o tipo do sensor da peça.
        -data_quebra: Campo que armazena um valor que marca a data de previsão de um defento.
        -placa_peça: Campo que armazena a placa do veiculo, para se obter o historico de defeitos.
        -id_sensor: Campo com o ID do sensor utilizado para verificar possiveis defeitos.
    
    
    
### 6	MODELO LÓGICO<br>
<img src=https://github.com/carroBD/trab01/blob/master/Imagens/Logico_2.png/>

### 7	MODELO FÍSICO<br>
        create table cliente (
	nome varchar(100) not null,
	cpf varchar(11) not null,
	carro_cliente char(50) not null,
	email_cliente varchar(50) not null,
	telefone_cliente varchar(50) not null
);

create table mecanico(
	cnpj int not null,
	nome_oficina varchar(50) not null,
	cpf_cliente varchar(11) not null,
	nome varchar(100) not null
);

create table categoria_veiculo(
	modelo_veiculo varchar(50),
	placa_veiculo varchar(7),
	historico_defeito date
);

create table veiculo(
	placa char(7) not null,
	id_veiculo serial not null,
	cpf_dono varchar(11)
);

create table dados(
	situacao_peca varchar(100),
	tempo_defeito varchar(50),
	tipo_defeito varchar(50),
	previsao_falha date,
	id_dados serial
);

create table sensor(
	id_sensor serial not null,
	analise_peca varchar(50) not null,
	peca_sensor varchar(50) not null
);

create table historico(
	sensor_peca varchar(50),
	data_quebra date,
	placa_peca varchar(50),
	id_sensor_historico serial
);       
        
### 8	INSERT APLICADO NAS TABELAS DO BANCO DE DADOS<br>
#### 8.1 DETALHAMENTO DAS INFORMAÇÕES
      
insert into cliente (nome,cpf,carro_cliente,email_cliente,telefone_cliente)
values('luciano','1111','bmw','luciano@gmail.com','27998664312'),('matheus','2222','renault','matheus@gmail.com','27998632145'),
('joao','3333','bugre','joao@gmail.com','27985476321'),('harrison','4444','citroen','harrison@gmail.com','986533214'),
('nicolas','5555','toyota','nicolas@gmail.com','2799853213'),('daniel','6666','volvo','daniel@gmail.com','27996553212'),
('andreas','7777','volkswagen','andreas@gmail.com','27987554213'),('rafael','8888','kia','rafael@gmail.com','27998654213'),
('wallace','9999','hyundai','wallace@gmail.com','27985512342'),('gabriela','1333','fiat','gabriela@gmail.com','27889654513');


insert into historico(sensor_peca,data_quebra,placa_peca,id_sensor_historico)
values('carburador','19-02-20','MTE8981',1),('motor','18-09-13',
'MRM7739',3),('correiadentada','19-04-14','MSN3214',22),('suspensao','18-11-15','MTC0872',9),('pastilhadefreio','19-10-10','MRD6416',5),('filtrodear','19-10-04','MQG1140',10),
('rolamento','19-01-13','MPD8181',8),('bateria','19-12-12','MSR5954',4);

insert into veiculo(placa,id_veiculo,cpf_dono)
values('MTE8981',1,'1111'),('MTJ7306',2,'2222'),('MRM7739',3,'3333'),('MSN3214',4,'4444'),('MTC0872',5,'5555'),('MTK7829',6,'6666'),('MRD6416',7,'7777'),('MQG1140',8,'8888'),('MPD8181',9,'9999'),('MSR5954',10,'1133');

insert into sensor(id_sensor,analise_peca,peca_sensor)
values(1,'quebrado' ,'carburador'),(3, 'quebrado','motor'),(4, 'quebrado','motor'),(22,'quebrado','correiadentada'),(9,'quebrado','suspensao'),(5,'quebrado','pastilhadefreio'),(10,'quebrado','filtrodear'),(8,'quebrado','rolamento'),(70,'quebrado','bateria');

insert into categoria_veiculo(modelo_veiculo,placa_veiculo,historico_defeito)
values('x5','mte8981','2018-09-27'),('clio','mtj7306','2018-09-27'),('buggy','mrm7739','2018-09-27'),('ds3','msn3214','2018-09-27'),('hilux','mtc0872','2018-09-27'),('s80','mtk7829','2018-09-27'),('amarok','mrd6416','2018-09-27'),('soul','mqg1140','2018-09-27'),('h1','mpd8181','2018-09-27'),('uno','msr5954','2018-09-27');

insert into mecanico(nome,nome_oficina,cnpj,cpf_cliente)
values('marcos','pedrao',1010,1111),('claudio','claudao','2020','2222'),('jose','ze','3030','3333'),('pedro','pedrao','4040','4444'),('luis','luisao','5050','5555'),('fabio','cruz','6060','6666'),('tiago','fabao','7070','7777'),('andre','dinao','8080','8888'),('onofre','jacinto','9090','9999'),('harrison','sanchez','1133','1333');

insert into dados(situacao_peca,tempo_defeito,tipo_defeito,previsao_falha,id_dados)
values('ruim',30,'carburador','19-02-20',1),('ruim',20,'motor','18-12-11',2),('pessima',10,'motor','18-09-13',3),('ruim',30,'correiadentada','19-04-14',22),('ruim',30,'suspensao','18-11-15',9),('pessima',10,'suspensao','19-01-04',4),('ruim',20,'pastilhadefreio','19-10-10',5),('ruim',40,'filtrodear','19-10-04',10),('pessimo',5,'rolamento','19-01-13',8),('ruim',15,'bateria','19-12-12',12)


#### 8.2 INCLUSÃO DO SCRIPT PARA CRIAÇÃO DE TABELAS E INSERÇÃO DOS DADOS
        a) Junção dos scripts anteriores em um único script 
        (create para tabelas e estruturas de dados + dados a serem inseridos)
        b) Criar um novo banco de dados para testar a restauracao 
        (em caso de falha na restauração o grupo não pontuará neste quesito)
        c) formato .SQL
#### 8.3 INCLUSÃO DO SCRIPT PARA EXCLUSÃO DE TABELAS EXISTENTES, CRIAÇÃO DE TABELA NOVAS E INSERÇÃO DOS DADOS
        a) Junção dos scripts anteriores em um único script
        (Drop para exclusão de tabelas + create para tabelas e estruturas de dados + dados a serem inseridos)
        b) Criar um novo banco de dados para testar a restauracao 
        (em caso de falha na restauração o grupo não pontuará neste quesito)
        c) formato .SQL
>## Marco de Entrega 03 em: (27/09/18) <br>

### 9	TABELAS E PRINCIPAIS CONSULTAS<br>
    OBS: Incluir para cada tópico as instruções SQL + imagens (print da tela) mostrando os resultados.<br>
#### 9.1	CONSULTAS DAS TABELAS COM TODOS OS DADOS INSERIDOS (Todas) <br>
#### 9.2	CONSULTAS DAS TABELAS COM FILTROS WHERE (Mínimo 4)<br>
#### 9.3	CONSULTAS QUE USAM OPERADORES LÓGICOS, ARITMÉTICOS E TABELAS OU CAMPOS RENOMEADOS (Mínimo 11)
    a) Criar 5 consultas que envolvam os operadores lógicos AND, OR e Not
    b) Criar no mínimo 3 consultas com operadores aritméticos 
    c) Criar no mínimo 3 consultas com operação de renomear nomes de campos ou tabelas
#### 9.4	CONSULTAS QUE USAM OPERADORES LIKE E DATAS (Mínimo 12) <br>
    a) Criar outras 5 consultas que envolvam like ou ilike
    b) Criar uma consulta para cada tipo de função data apresentada.

#### 9.5	ATUALIZAÇÃO E EXCLUSÃO DE DADOS (Mínimo 6)<br>

>## Marco de Entrega 04 em: (18/10/2017)<br>

#### 9.6	CONSULTAS COM JUNÇÃO E ORDENAÇÃO (Mínimo 6)<br>
        a) Uma junção que envolva todas as tabelas possuindo no mínimo 3 registros no resultado
        b) Outras junções que o grupo considere como sendo as de principal importância para o trabalho
#### 9.7	CONSULTAS COM GROUP BY E FUNÇÕES DE AGRUPAMENTO (Mínimo 6)<br>
#### 9.8	CONSULTAS COM LEFT E RIGHT JOIN (Mínimo 4)<br>
#### 9.9	CONSULTAS COM SELF JOIN E VIEW (Mínimo 6)<br>
        a) Uma junção que envolva Self Join
        b) Outras junções com views que o grupo considere como sendo de relevante importância para o trabalho
#### 9.10	SUBCONSULTAS (Mínimo 3)<br>
### 10	ATUALIZAÇÃO DA DOCUMENTAÇÃO DOS SLIDES PARA APRESENTAÇAO FINAL (Mínimo 6 e Máximo 10)<br>

### 11 Backup completo do banco de dados postgres 
    a) deve ser realizado no formato "backup" 
        (Em Dump Options #1 Habilitar opções Don't Save Owner e Privilege)
    b) antes de postar o arquivo no git o mesmo deve ser testado/restaurado por outro grupo de alunos/dupla
    c) informar aqui o grupo de alunos/dupla que realizou o teste.

### 12	TUTORIAL COMPLETO DE PASSOS PARA RESTAURACAO DO BANCO E EXECUCAO DE PROCEDIMENTOS ENVOLVIDOS NO TRABALHO PARA OBTENÇÃO DOS RESULTADOS<br>
        a) Outros grupos deverão ser capazes de restaurar o banco 
        b) executar todas as consultas presentes no trabalho
        c) executar códigos que tenham sido construídos para o trabalho 
        d) realizar qualquer procedimento executado pelo grupo que desenvolveu o trabalho
        
### 13   DIFICULDADES ENCONTRADAS PELO GRUPO<br>
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


