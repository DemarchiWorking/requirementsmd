![header](https://mma.prnewswire.com/media/1807381/Stefanini_Group_Logo.jpg?p=facebook)

<b><h1 align="right">Portal Itaú 2.0</h1></b>
<h3 align="right">Documento de Requisitos</h3>
<b><p align="right">	
Simplificado </br>
Versão 1.0 </br>
2022 </br>
</p></b>
<img src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge" align="right"/> </br>

<b><h4 align="center"><caption>Histórico de Revisões</caption></h4></b>
<table align="center">
  <tr>
    <td>Data</td>
    <td>Versão</td>
    <td>Descrição</td>
    <td>Autor</td>
  </tr>
  <tr>
    <td>26-08-2022</td>
    <td>1.0</td>
    <td>Versão inicial do documento.</td>
    <td> 211 </td>
  </tr>
</table>
</br>

----------------------------------------

<h5 align="right"> Índice </h5>
<table align="center">
  <tr>
	<td><b>1</b></td>
    <td><b>INTRODUÇÃO</b></td>
    <td> 4 </td>
  </tr>
  <tr>
    <td> &nbsp;&nbsp; 1.1</td>
    <td> &nbsp; &nbsp; &nbsp; Propósito do documento de requisitos </td>
    <td> 4 </td>
  </tr>
  <tr>
    <td> &nbsp;&nbsp;1.2</td>
    <td> &nbsp; &nbsp; &nbsp;Escopo do produto </td>
    <td> 4 </td>
  </tr>
  <tr>
    <td> &nbsp;&nbsp;1.3</td>
    <td> &nbsp;&nbsp;&nbsp;Concepção do sistema </td>
    <td> 4 </td>
  </tr>
  <tr>
    <td> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.4.1</td>
    <td> &nbsp;&nbsp;&nbsp;Convenções, termos e abreviações </td>
    <td> 4 </td>
  </tr>
  <tr>
    <td> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.4.2</td>
    <td> &nbsp;&nbsp;&nbsp;Prioridade dos Requisitos </td>
    <td> 4 </td>
  </tr>
  <tr>
    <td> &nbsp;&nbsp;1.5</td>
    <td> &nbsp;&nbsp;&nbsp;Referências </td>
    <td> 5 </td>
  </tr>
  <tr>
    <td> &nbsp;&nbsp;1.6</td>
    <td> &nbsp;&nbsp;&nbsp; Visão Geral</td>
    <td> 5 </td>
  </tr>
 <tr>
	 <td><b>2</b></td>
    <td> <b>DESCRIÇÃO GERAL</b></td>
    <td> 6 </td>
  </tr>
  <tr>
    <td> &nbsp;&nbsp; 2.1</td>
    <td> &nbsp;&nbsp;&nbsp;Usuários do sistema </td>
    <td> 6 </td>
  </tr>
  <tr>
    <td> &nbsp;&nbsp; 2.2</td>
    <td> &nbsp;&nbsp;&nbsp; Abrangência e sistemas similares </td>
    <td> 6 </td>
  </tr>
  <tr>
    <td> &nbsp;&nbsp; 2.3</td>
    <td> &nbsp;&nbsp;&nbsp;Suposições e dependências</td>
    <td> 6 </td>
  </tr>
  <tr>
	  <td><b>3</b></td>
    <td> <b>REQUISITOS DO SOFTWARE</b></td>
    <td> 7 </td>
  </tr>
  <tr>
    <td> &nbsp;&nbsp; 3.1</td>
    <td> &nbsp;&nbsp;&nbsp;Requisitos Funcionais </td>
    <td> 7 </td>
  </tr>
  <tr>
    <td> &nbsp;&nbsp; 3.2</td>
    <td> &nbsp;&nbsp;&nbsp;Requisitos Não-funcionais </td>
    <td> 7 </td>
  </tr>
  <tr>
    <td> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 3.2.1</td>
    <td> &nbsp;&nbsp;&nbsp;Requisitos de Segurança </td>
    <td> 7 </td>
  </tr>
  <tr>
    <td> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 3.2.2</td>
    <td> &nbsp;&nbsp;&nbsp;Requisitos de Interface </td>
    <td> 7 </td>
  </tr>
  <tr>
    <td> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 3.2.3</td>
    <td> &nbsp;&nbsp;&nbsp;Requisitos de Operacionais </td>
    <td> 7 </td>
  </tr>
  <tr>
    <td> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 3.2.4</td>
    <td> &nbsp;&nbsp;&nbsp;Requisitos de Confiabilidade </td>
    <td> 8 </td>
  </tr>
  <tr>
	  <td><b>4</b></td>
    <td><b>CASOS DE USO</b></td>
    <td> 9 </td>
  </tr>
  <tr>
    <td> &nbsp;&nbsp; 4.1</td>
    <td> &nbsp;&nbsp;&nbsp;Diagrama de casos de uso </td>
    <td> 9 </td>
  </tr>
  <tr>
    <td> &nbsp;&nbsp; 4.1.1</td>
    <td> &nbsp;&nbsp;&nbsp;Usuário </td>
    <td> 9 </td>
  </tr>
  <tr>
    <td> &nbsp;&nbsp; 4.2</td>
    <td> &nbsp;&nbsp;&nbsp;Descrição dos casos de uso </td>
    <td> 9 </td>
  </tr>
   <tr>
	   <td><b>5</b></td>
	   <td><b>Classe</b></td>
    <td> 10 </td>
  </tr>
  <tr>
    <td> &nbsp;&nbsp; 5.1</td>
    <td> &nbsp;&nbsp;&nbsp;Diagrama de Classe</td>
    <td> 10 </td>
  </tr>
</table>


<h1>Documento de Requisitos</h1>
</br></br>
<h2 align="right">Introdução</h2>


 <h5> 1.1 &nbsp;&nbsp;&nbsp;&nbsp; Propósito do documento de requisitos</h5>

<p>Documentação tem o intuito de expressar as funcionalidades do sistema.</p>


1.2 &nbsp;&nbsp;&nbsp; <h5>Escopo do produto</h5><br>

<i>O projeto consiste na documentação e refatoração de um portal, utilizando uma arquitetura de microsserviços. </i>
<p><b>Autenticacao</b> - Um projeto em .Net Core para autenticação, criptografia e segurança.
<b>Faturamento</b> - Um microsserviço para as funcionalidades de faturamento.
<b>Indicadores</b> - Um microsserviço para funcionalidades relacionadas aos indicadores.
<b>Administrativo</b> - Um microsserviço  para o painel de controle e visualização de logs.	
</p>

1.3 &nbsp;&nbsp;&nbsp; <h5">Concepção do sistema</h5><br>
<p>
N/D
</p>


1.4 &nbsp;&nbsp;&nbsp; <h5>Concepção do sistema</h5><br>
<p>
N/D
</p>

1.5 &nbsp;&nbsp;&nbsp; <h5> Convenções, termos e abreviações </h5>
<p>
Para evitar interpretações incorretas deste documento, algumas convenções e termos específicos são descritos a seguir:
</p>

<table align="center">
  <tr>
    <td>RPA</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Automação robótica de processos</td>
    <td></td>
    <td></td>
  </tr>
</table>

XXXXX

Identificação dos Requisitos
Cada requisito será unicamente identificado no formato [tipoRequisito.numero]. Para requisitos funcionais, o código do tipo de requisito será RF, e para requisitos não funcionais, RNF. Um número será assinalado a cada requisito de forma incremental, na ordem que forem mencionados neste documento.

Prioridade dos Requisitos
Foram adotadas as seguintes denominações para estabelecer a prioridade dos requisitos: essencial, importante e desejável. 
Essencial: é o requisito sem o qual o sistema não entra em funcionamento, ou seja, são requisitos imprescindíveis tendo que ser implementados impreterivelmente. 
Importante: é o requisito sem o qual o sistema entra em funcionamento, mas de maneira insatisfatória, ou seja, devem ser implementados, mas se não forem, o sistema poderá ser implantado e usado mesmo assim.
Desejável: é o requisito que não compromete as funcionalidades básicas do sistema, podendo funcionar de forma satisfatória sem ele, ou seja, são requisitos que podem ser deixados para versões posteriores do sistema, caso não haja tempo hábil para implementá-los na versão que está sendo especificada. 

Referências

N/D
Visão Geral
Este documento está organizado da seguinte forma:
A seção 1 apresentou uma introdução ao documento de requisitos e ao sistema sendo especificado;
A seção 2 apresenta uma descrição geral do sistema;
A seção 3 apresenta as definições dos requisitos funcionais e não-funcionais do sistema;
A seção 4 apresenta o diagrama de casos de uso do sistema, bem como as descrições dos casos de uso definidos;



































Descrição geral
Portal Itaú 2.0
_______________________________________________________________________________________________________________________________________________________________________________________________________
					Documento de Requisitos
_______________________________________________________________________________________________________________________________________________________________________________________________________
Introdução
Usuários do Sistema
Usuário: Tem acesso a funções do sistema (exemplo: gestão,  faturamento, fornecedores, indicadores entre outros).

Administrador: Tem acesso ao painel administrativo e aos logs do sistema.

Abrangência e sistemas similares
Abrangência:  
O sistema terá como objetivo carregar, visualizar e processar informações estratégicas do Itaú.

Sistemas similares: 
Portal
Aplicações de RPA.
Bots.


Suposições e dependências
As seguintes suposições são válidas no decorrer do desenvolvimento do sistema sendo especificado:
O cliente está responsável pela aquisição de infraestrutura necessária em seu ambiente de produção;



































Requisitos do Software 

Requisitos Funcionais

Aplicação 1 - Portal Itaú 2.0
<RF01>Cadastro de Usuários
O sistema deverá ter um formulário para cadastro de novos usuários.

<RF02>Login
O sistema deverá mostrar informações apenas para usuários que fizerem login com suas credenciais de acesso.

<RF03>Logoff
O sistema deverá encerrar a sessão do usuário atual.

Requisitos Não-funcionais
Os requisitos que descrevem os aspectos não-funcionais do sistema são apresentados a seguir:

Requisitos de Segurança
Ident.
Descrição
Casos de uso relacionados
RNF/SEG-01
O usuário autorizado deverá efetuar login para poder realizar as operações no sistema.



Requisitos de Interface
Ident.
Descrição
Casos de uso relacionados
RNF/INT-01
O sistema deve ter uma interface amigável, de fácil utilização, ou seja, auto explicável. 



Requisitos de Operacionais
Ident.
Descrição
Casos de uso relacionados
RNF/OPE-01
O sistema deve ser desenvolvido em C#


RNF/OPE-02
O sistema deverá ter uma arquitetura de microsserviços


RNF/OPE-03
A camada de aplicação para web deverá ser compatível com browser do Google Chrome.



Requisitos de Confiabilidade
Ident.
Descrição
Casos de uso relacionados
RNF/CON-01
O sistema deverá  armazenar os logs.





Casos de uso
Diagrama de casos de uso
O diagrama de casos de uso, expresso em UML (Unified Modeling Language), expressa os requisitos funcionais do sistema na forma de casos de uso. Segundo o RUP (Rational Unified Process), para cada requisito funcional tem-se um caso de uso. A descrição textual detalhada dos requisitos funcionais, seus fluxos de atividades e requisitos não funcionais associados pode ser encontrada na próxima seção. Na figura abaixo mostramos a representação gráfica em UML dos casos de uso do sistema.


[CDU-01]
Nome:
Realizar atividades
Atores:
Usuário
Prioridade:
Essencial
Requisitos associados:
[RNF/SEG-01]
Entradas e pré-condições:
O usuário deverá executar a aplicação.
Saídas e pós-condições:
O usuário consegue realizar as atividades.
Fluxos de eventos
Fluxo principal:
O usuário inicia uma sessão no sistema.
O usuário escolhe a opção faturamento.
O usuário pode visualizar o faturamento.










Diagrama de Classes









> Status: Developing ⚠️




### It is a web application planned by me, where I perform the CRUD of Calisthenics Movements.

## Some fields in main Model is:

+ name 
+ description
+ repetation num
+ sequency num
+ dificult category
+ i know
+ user_id
+ image
  
Also that, has a User with this fields:

+ name
+ email
+ cpf
+ birth
+ active

## In addition to CRUD, I implement other features such as:

* See the more recently movement created, using Cookie.
* Entire verification system to validate forms with personalized messages.
* Message of success when create a movement, using Session Flash.
* Profile User editable.

## This features are in developing:

- Search for movements by name and/or dificulted category.
- Email verification.

## Technologies Used:

<table>
  <tr>
    <td>PHP</td>
    <td>Laravel</td>
    <td>Composer</td>
    <td>MySql</td>
  </tr>
  <tr>
    <td>6.*</td>
    <td>7.4</td>
    <td>2.0</td>
    <td>8.0</td>
  </tr>
</table>

## How to run the application:

1) run shell: 
2) run shell: 
3) create new Schema
4) create file .env
5) configure your database variables in .env
6) run shell: 

