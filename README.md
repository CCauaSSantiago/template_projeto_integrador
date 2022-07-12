# TRABALHO DE PI:  Título do Trabalho
Trabalho desenvolvido durante a disciplina de Banco de Dados do Integrado

# Sumário

### 1. COMPONENTES<br>
Integrantes do grupo<br>
Cauã Santiago:ccauassantiago77@gmail.com<br>
...

### 2.MINIMUNDO<br>

> Uma empresa deseja um sistema em que possa cadastrar o cliente e realizar pedidos referentes a seus produtos. Do cliente a empresa necessita dos seguintes dados: código, usuário, nome, senha, endereço, o valor depositado e seu endereço de e-mail. Um cliente pode estar relacionado a nenhum ou vários pedidos mas um pedido deve estar relacionado a no minimo um e apenas a um cliente. Do pedido devemos armazenar: código, data_hora, observação. Cada pedido contém um ou vários produtos, e cada produto esta contido em vários pedidos ou em nenhum. O produto deve conter: código, preço, nome, tipo_produto, é necessário armazenar a quantidade dos produtos.
 
 
### 3.PMC<br>

a) inclusão do PMC desenvolvido pelo grupo <br>


![Imagem do PMC](https://github.com/CCauaSSantiago/template_projeto_integrador/blob/main/arquivos/pmc.png)


### 4.Personas e Histórias de usuário<br>
Cauã Santiago:

18 anos
Masculino 
Estudante

Perfil: 

Cauã é uma pessoa ansiosa e impaciente, tenta fazer muitas coisas ao mesmo tempo, como os
deveres e afazeres do Ifes e de casa, mais os seus trabalhos pessoais quando pode, por isso está o
sempre casando.
Por passar maior parte de seu tempo no Ifes sempre necessita de um café para repor as energias,
porém o processo de realização do atendimento da cantina, supera o seu tempo de intervalo.

Necessidades:

Um Sistema com menu.

Um sistema em que eu posso ver as principais comidas antes de eu acessar o cardápio no menu.

Um sistema em eu que possa ver o cardápio.

Um sistema em que possa acessar e depositar o meu pré-pago.
<br>

Aghata Oliveira da Silva:

24 anos
Atendente da Cantina Do Ifes Campus Serra
Sexo Feminino

Perfil:

Aghata tem uma rotina de trabalho estressante, ela não gosta de interagir muito com pessoas, isso se
deve porque sua irmão esta passando pela fazer adolescente dramática, trabalhando no Ifes onde
grande parte de pessoas são adolescentes, ela só gostaria de trabalhar sem ter muito contato com
adolescentes
<br>

Gileard Sousa Pinto:

30 anos
Cozinheiro da Cantina Do Ifes Campus Serra
Sexo masculino

Perfil:

Gileard gosta das coisas bem organizadas, seu passatempo favorito é arrumar sua casa e cozinhar
coisas novas. Em seu trabalho é o melhor, junto com a sua equipe sempre deixa o cardápio pronto
paras as primeiras horas de pico, porém, nem sempre de um intervalo para outro é possível repor
todo o cardápio e nem de avisar os clientes, Gileard precisa de um sistema que seja possível
informar seus clientes do cardápio.
<br>

### 5.RASCUNHOS BÁSICOS DA INTERFACE (MOCKUPS)<br>

![imagem prototipo](https://github.com/CCauaSSantiago/template_projeto_integrador/blob/main/arquivos/prototipo.png)


#### 5.1 QUAIS PERGUNTAS PODEM SER RESPONDIDAS COM O SISTEMA PROPOSTO?
    a) O sistema proposto poderá fornecer quais tipos de relatórios e informaçes? 
    b) Crie uma lista com os 5 principais relatórios que poderão ser obtidos por meio do sistema proposto!
    
Relatório da página de login que informa quais são os clientes ao logarem incluindo as seguintes informações: Matrícula e senha.
Relatório da página de menu incluindo as seguintes informações: Cardápio, depositar pré—pago.
Relatório da página de Cardápio que informa quais são os tipos de lanches e os lanches de cada categoria.
Relatório da página de pedido que informa informações sobre o pedido feito e sobre o pré-pago incluindo as seguintes informações: comanda, observação, valor total, pré-pago.
Relatório da página de pré-pago que informa quais são as opções de depósito incluindo os bancos virtuais e o valor depositado.
 

### 6 TABELA DE DADOS DO SISTEMA:
    A) Esta tabela deve conter **todos os atributos do sistema** e um mínimo de 10 linhas/registros de dados.
    B) Esta tabela tem a intenção de simular um relatório com todos os dados que serão armazenados 
       (veja o exemplo abaixo antes de criar a tabela para seu trabalho)
    C) Após criada esta tabela não deve ser modificada, pois será comparada com os resultados finais na conclusão do trabalho
    

![](https://github.com/CCauaSSantiago/template_projeto_integrador/blob/main/arquivos/conceitual.pdf)

 
 
 ### 7.MODELO CONCEITUAL<br>
    A) Utilizar a Notação adequada (Preferencialmente utilizar o BR Modelo 3)
    B) O mínimo de entidades do modelo conceitual pare este trabalho será igual a 4.
        * informe quais são as 3 principais entidades do sistema em densenvolvimento
      (se houverem mais de 3 entidades, pense na importância da entidade para o sistema)       
    C) Principais fluxos de informação/entidades do sistema (mínimo 2). <br>Dica: normalmente estes fluxos estão associados as tabelas que conterão maior quantidade de dados 
    D) Qualidade e Clareza
        Garantir que a semântica dos atributos seja clara no esquema (nomes coerentes com os dados).
        Criar o esquema de forma a garantir a redução de informação redundante, possibilidade de valores null, 
        e tuplas falsas (Aplicar os conceitos de normalização abordados).   
        
![](https://github.com/CCauaSSantiago/template_projeto_integrador/blob/main/arquivos/conceitualV2100722.png)
    
#### 7.1 Descrição dos dados 
    [objeto]: [descrição do objeto]
    
    EXEMPLO:
    CLIENTE: Tabela que armazena as informações relativas ao cliente<br>
    CPF: campo que armazena o número de Cadastro de Pessoa Física para cada cliente da empresa.<br>

### 8	RASTREABILIDADE DOS ARTEFATOS<br>
        a) Historia de usuários vs protótipo (mockup)
        b) Protótipo vs Modelo conceitual
        (não serão aceitos modelos que não estejam em conformidade)
        c) Backlog (caso solicitado)

### 9	MODELO LÓGICO<br>
![](https://github.com/CCauaSSantiago/template_projeto_integrador/blob/main/arquivos/LogicoV2100722.png)

### 10	MODELO FÍSICO<br>
        a) inclusão das instruções de criacão das estruturas em SQL/DDL 
        (criação de tabelas, alterações, etc..) 
        
       
### 11	INSERT APLICADO NAS TABELAS DO BANCO DE DADOS<br>
        a) inclusão das instruções de inserção dos dados nas tabelas criadas pelo script de modelo físico
        (Drop para exclusão de tabelas + create definição de para tabelas e estruturas de dados 
 <br> + insert para dados a serem inseridos)
        b) Criar um novo banco de dados para testar a restauracao 
        (em caso de falha na restauração o grupo não pontuará neste quesito)
        c) formato .SQL


### 12	TABELAS E PRINCIPAIS CONSULTAS<br>
    OBS: Incluir para cada tópico as instruções SQL + imagens (print da tela) mostrando os resultados.<br>
#### 12.1	CONSULTAS DAS TABELAS COM TODOS OS DADOS INSERIDOS (Todas) <br>
#### 12.2 PRINCIPAIS CONSULTAS DO SISTEMA 
 Inserir as principais consultas (relativas aos 5 principais relatórios) definidas previamente no iten 3.1 deste template.
 <br>
  a) Você deve apresentar as consultas em formato SQL para cad um dos relatórios.
 <br>
  b) Além da consulta deve ser apresentada uma imagem com o resultado obtido para cada consulta.<br>
 #### 12.3 ANTEPROJETO VERSÃO 1
 
 Link para [Modelo de Anteprojeto](https://docs.google.com/document/d/1oeVS2CUffbSNYWxIWZFY_mX6E5ao_PHU/edit?usp=sharing&ouid=104104747195236161434&rtpof=true&sd=true)
 
 <br>
 <br>
 
 
 ### 13 Gráficos, relatórios, integração com Linguagem de programação e outras solicitações.<br>
     OBS: Observe as instruções relacionadas a cada uma das atividades abaixo.<br>
 #### 13.1	Integração com Linguagem de programação; <br>
 #### 13.2	Desenvolvimento de gráficos/relatórios pertinentes, juntamente com demais <br>
 #### solicitações feitas pelo professor. <br>
 #### 13.3 ANTEPROJETO VERSÃO 2
 <br>
 <br>
 
 
 ### 14 Slides e Apresentação em vídeo. <br>
     OBS: Observe as instruções relacionadas a cada uma das atividades abaixo.<br>
 #### 14.1 Slides; <br>
 #### 14.2 Apresentação em vídeo <br>
 #### 14.3 ANTEPROJETO VERSÃO FINAL
 <br>
 <br>   


    
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

#### Todos os grupos deverão fazer Fork deste repositório e dar permissões administrativas ao usuário deste GIT, para acompanhamento do trabalho.

#### Os usuários criados no GIT devem possuir o nome de identificação do aluno (não serão aceitos nomes como Eu123, meuprojeto, pro456, etc). Em caso de dúvida comunicar o professor.


Link para BrModelo:<br>
http://sis4.com/brModelo/brModelo/download.html
<br>


Link para curso de GIT<br>
![https://www.youtube.com/curso_git](https://www.youtube.com/playlist?list=PLo7sFyCeiGUdIyEmHdfbuD2eR4XPDqnN2?raw=true "Title")
