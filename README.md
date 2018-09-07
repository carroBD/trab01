# TRABALHO 01:  Smart Car
Trabalho desenvolvido durante a disciplina de BD1

# Sumário

### 1. COMPONENTES<br>
Integrantes do grupo
    <ol>Harrison Sanches: harrison.sanches@gmail.com</ol>
    <ol>João Augusto: joao.augusto1809@gmail.com</ol>
    <ol>Luciano Barboza: luciano.ananias.50@gmail.com</ol>
    <ol>Matheus Comério: matheuscomerior@gmail.com</ol>
### 2.INTRODUÇÃO E MOTIVAÇAO<br>

O grande número de acidentes nas rodovias brasileiras, e o elevado número de mortes proveniente desse assunto, é um dos grandes problemas existentes no país. Considerado como problema de saúde pública, o Brasil aparece em quinto lugar entre os países recordistas em mortes no trânsito, atrás da Índia, China, EUA e Rússia. Segundo o Ministério da Saúde, em 2015, foram registrados 37.306 óbitos e 204  mil pessoas ficaram feridas . 
Em 2016, só na microrregião metropolitana no Estado do Espírito Santo, foram 23.190 mortes.
https://github.com/carroBD/trab01/blob/master/Imagens/Capturar.PNG
As causas dos acidentes são variadas. Segundo o portal do trânsito brasileiro, as maiores causas destes acidentes são: Excesso de velocidade; Desrespeito à sinalização; Ingestão de bebidas alcoólicas e, liderando, Imprudência.
Acerca da imprudência, estão diversos fatores, principalmente a não revisão veicular e falhas mecânicas dos componentes veiculares, provenientes do descaso dos motoristas com seus veículos. E é em cima desse problema que o sistema “Smart Car” visa colaborar. O sistema tem como finalidade gerenciar os componentes mecânicos do carro (giro do motor, pistão, pneus, precisão dos controles) a fim de gerar dados sobre esses componentes e prever possíveis falhas, evitando os acidentes por falhas mecânicas nas estradas. O sistema visa atuar também em cima do dinamismo acerca do tempo da sociedade contemporânea , impactando no ganho de tempo no cotidiano do usuário, possibilitando, por exemplo, que o usuário do sistema, ao ser notificado de um possível risco de falha de um componente, possa agendar diretamente, com um mecânico de sua escolha, uma revisão ou troca do componente, agilizando sua rotina e trabalho de vistoria do mecânico, evitando perda de tempo para ambas as partes. Para isso, o sistema contará com sensores de controle, gerando dados sobre os componentes, e possibilitará o cadastro do carro e de mecânicos especializados escolhidos e cadastrados pelo cliente para contato. O sistema notificará com um tempo satisfatório uma possível falha de algum componente e deverá armazenar esses dados de falhas em bancos de dados para possíveis novas análises. 

### 3.MINI-MUNDO Novo<br>
O sistema “Smart Car” proposto tem por objetivo a inspeção e análise  veicular, a fim de gerar análises dos componentes do veículo. Acerca das inspeções, cada carro contará com sensores, cada sensor é associado a um, e somente um, componente do carro. O carro poderá contar com mais de um sensor e cada carro terá um motorista a ele associado. Cada sensor terá seu nome de identificação, finalidade e identificação associando em qual carro está inserido. Será necessário um cadastro do cliente com nome e cpf, para identificação. No que tange ao carro, será necessário armazenar todas as informações sobre o veículo, como chassi, placa, ano, modelo, e seus respectivos componentes instalados. Cada carro poderá ter um, e somente um, motorista associado. O sistema deve ser capaz de notificar o usuário de forma simples e clara, a fim de especificar com clareza a possível falha de algum componente. O sistema deve realizar cadastro de mecânicos, escolhidos pelo usuário, a fim de estabelecer um contato entre os dois agentes. Deverá permitir também um contato de forma simples e direta, com a possibilidade de cadastro de mais de um mecânico por cliente. O sistema não ficará responsável pelo controle de peças por parte do mecânico, o mesmo apenas estabelecerá um contato entre cliente-mecânico, a fim de ambos chegaram a um consenso para possível revisão/troca do componente. O sistema não fornecerá dados do componentes instalados no carro do motorista, por questão de privacidade e risco de possíveis fraudes nos componentes ou na hora do serviço prestado. No momento do contato, será informado apenas a data da possível falha e respectivo componente que poderá ocorrer a falha. O sistema contará com diferenciação no cadastro entre ser cliente ou mecânico.a fim de proporcionar telas diferentes para ambos. Na tela do mecânico contará apenas os clientes que o adicionaram ao usar o programa. Será necessário captar os dados como Nome, CPF, nome da oficina, CNPJ e demais informações a fim de prover controle e segurança para os clientes. Com  Já a tela do motorista contará com dados dos sensores, sensores instalados, carros cadastrados, mecânicos cadastrados e área para contato com o mecânico que assim desejar.


### 4.RASCUNHOS BÁSICOS DA INTERFACE (MOCKUPS)<br>
Neste ponto a codificação não e necessária, somente as ideias de telas devem ser criadas, o princípio aqui é pensar na criação da interface para identificar possíveis informações a serem armazenadas ou descartadas <br>

Sugestão: https://balsamiq.com/products/mockups/<br>

![Alt text](https://github.com/discipbd1/trab01/blob/master/balsamiq.png?raw=true "Title")
![Arquivo PDF do Protótipo Balsamiq feito para Empresa Devcom](https://github.com/discipbd1/trab01/blob/master/arquivos/EmpresaDevcom.pdf?raw=true "Empresa Devcom")
#### 4.1 QUAIS PERGUNTAS PODEM SER RESPONDIDAS COM O SISTEMA PROPOSTO?
    a) O sistema proposto poderá fornecer quais tipos de relatórios e informaçes? 
    b) Crie uma lista com os 5 principais relatórios que poderão ser obtidos por meio do sistema proposto!
   - Relatório geral sobre a situação do carro do cliente<ol>
   - Relatório de quais componentes do carro quebram com mais frequência
   - Relatório acerca da quais mecânicos estão mais disponíveis
   - Relatório de quais modelos de carro apresentam mais falhas
   - Relatório de Peça quebrada/Km rodado do modelo de carro.
   - Perfil dos motoristas.

 
#### 4.2 TABELA DE DADOS DO SISTEMA:
(https://github.com/carroBD/trab01/blob/master/Planilha/Planilha%20BD.xlsx "Tabela - SmartCar")
    
>## Marco de Entrega 01 em: (30/08/2018)<br>

### 5.MODELO CONCEITUAL<br>
    A) NOTACAO ENTIDADE RELACIONAMENTO 
        * Para nosso prótótipo limitaremos o modelo conceitual nas 6 principais entidades do escopo
        * O protótipo deve possui no mínimo duas relações N para N
        * o mínimo de entidades do modelo conceitual será igual a 5
        
![Alt text](https://github.com/discipbd1/trab01/blob/master/images/concept_sample.png?raw=true "Modelo Conceitual")
    
    B) NOTACAO UML (Caso esteja fazendo a disciplina de analise)
    C) QUALIDADE 
        Garantir que a semântica dos atributos seja clara no esquema
        Criar o esquema de forma a garantir a redução de informação redundante, possibilidade de valores null, 
        e tuplas falsas
    
        
    
#### 5.1 Validação do Modelo Conceitual
    [Grupo01]: [Nomes dos que participaram na avaliação]
    [Grupo02]: [Nomes dos que participaram na avaliação]

#### 5.2 DECISÕES DE PROJETO
    [atributo]: [descrição da decisão]
    
    EXEMPLO:
    a) Campo endereço: em nosso projeto optamos por um campo multivalorado e composto, pois a empresa 
    pode possuir para cada departamento mais de uma localização... 
    b) justifique!

>## Marco de Entrega 02 em: (13/09/2018)<br>
#### 5.3 DESCRIÇÃO DOS DADOS 
    [objeto]: [descrição do objeto]
    
    EXEMPLO:
    CLIENTE: Tabela que armazena as informações relativas ao cliente<br>
    CPF: campo que armazena o número de Cadastro de Pessoa Física para cada cliente da empresa.<br>


### 6	MODELO LÓGICO<br>
        a) inclusão do modelo lógico do banco de dados
        b) verificação de correspondencia com o modelo conceitual 
        (não serão aceitos modelos que não estejam em conformidade)

### 7	MODELO FÍSICO<br>
        a) inclusão das instruções de criacão das estruturas DDL 
        (criação de tabelas, alterações, etc..)          
        
### 8	INSERT APLICADO NAS TABELAS DO BANCO DE DADOS<br>
#### 8.1 DETALHAMENTO DAS INFORMAÇÕES
        a) inclusão das instruções de inserção dos dados nas tabelas criadas pelo script de modelo físico 
        b) formato .SQL

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


