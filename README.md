![header](https://mma.prnewswire.com/media/1807381/Stefanini_Group_Logo.jpg?p=facebook)

<p align=”left”> test </p>
<p align=”right”> test </p>

<table>
	<td><h1 style="text-align:left>Portal Itaú 2.0</h1></td>
</tr>
</table>
<br>
<h3 style="text-align:right">Documento de Requisitos</h3>
<p style="font-weight: bold;">Simplificado </br>
Versão 1.0 </br>
2022 </br>
</p>

<table>
  <caption>Histórico de Revisões</caption>
  <tr>
    <td>PHP</td>
    <td>Laravel</td>
    <td>Composer</td>
  </tr>
  <tr>
    <td>6.*</td>
    <td>7.4</td>
    <td>2.0</td>
  </tr>
  <tr>
    <td>6.*</td>
    <td>7.4</td>
    <td>2.0</td>
  </tr>
  <tr>
    <td>6.*</td>
    <td>7.4</td>
    <td>2.0</td>
  </tr>
</table>




-----------------------------------------------

Data
Versão
Descrição
Autor


1.0
Versão inicial do documento
211


























Portal Itaú 2.0
Índice
 
Nome do Sistema	4
1	INTRODUÇÃO	4
1.1	Propósito do documento de requisitos	4
1.2	Escopo do produto	4
1.3	Concepção do sistema	4
1.4	Convenções, termos e abreviações	4
1.4.1	Identificação dos Requisitos	4
1.4.2	Prioridade dos Requisitos	4
1.5	Referências	5
1.6	Visão Geral	5
2	DESCRIÇÃO GERAL	6
2.1	Usuários do sistema	6
2.2	Abrangência e sistemas similares	6
Sistemas similares:	6
2.3	Suposições e dependências	6
3	REQUISITOS DO SOFTWARE	7
3.1	Requisitos Funcionais	7
3.2	Requisitos Não-funcionais	7
3.2.1	Requisitos de Segurança	7
3.2.2	Requisitos de Interface	7
3.2.3	Requisitos de Operacionais	7
3.2.4	Requisitos de Confiabilidade	8
4	CASOS DE USO	9
4.1	Diagrama de casos de uso	9
4.1.1	Usuário	9
4.2	Descrição dos casos de uso	9
4	Classe	9
4.1	Diagrama de Classe








Portal Itaú 2.0
_______________________________________________________________________________________________________________________________________________________________________________________________________
					Documento de Requisitos
_______________________________________________________________________________________________________________________________________________________________________________________________________
Introdução

Propósito do documento de requisitos
Documentação tem o intuito de expressar as funcionalidades do sistema.
Escopo do produto
O projeto consiste na documentação e refatoração de um portal, utilizando uma arquitetura de microsserviços. 
Autenticacao - Um projeto em .Net Core para autenticação, criptografia e segurança.
Faturamento - Um microsserviço para as funcionalidades de faturamento.
Indicadores - Um microsserviço para funcionalidades relacionadas aos indicadores.
Administrativo - Um microsserviço  para o painel de controle e visualização de logs.

Concepção do sistema

N/D

Convenções, termos e abreviações
Para evitar interpretações incorretas deste documento, algumas convenções e termos específicos são descritos a seguir:
RPA
Automação robótica de processos










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

