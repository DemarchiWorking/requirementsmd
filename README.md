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

<h2 align="right"> Índice </h2>
<table align="center" border="0">
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

</br></br>
<h1>Documento de Requisitos</h1>
<h2 align="right">1 - Introdução</h2>


 <h3> 1.1 &nbsp;&nbsp;&nbsp;&nbsp; Propósito do documento de requisitos</h3>

<p>Documentação tem o intuito de expressar as funcionalidades do sistema.</p>


 <h3> 1.2 &nbsp;&nbsp;&nbsp;&nbsp; Escopo do produto</h3>
<p>O projeto consiste na documentação e refatoração de um portal, utilizando uma arquitetura de microsserviços. </p>

<ol>
  <ul>
	  <b>Autenticacao</b> <p>Um projeto em .Net Core para autenticação, criptografia e segurança. </p>
  </ul>
   <ul>
	  <b>Faturamento</b> <p>Um microsserviço para as funcionalidades de faturamento.</p>
  </ul>
  <ul>
	  <b>Indicadores</b> <p>Um microsserviço para funcionalidades relacionadas aos indicadores.</p>
  </ul>
  <ul>
	  <b>Administrativo</b> <p>Um microsserviço  para o painel de controle e visualização de logs.	</p>
	  </br>
  </ul>
</ol>
</br>

<h3> 1.3 &nbsp;&nbsp;&nbsp;&nbsp; Concepção do sistema</h3>  
<p>
&nbsp;&nbsp;&nbsp; N/D
</p>

<h3> 1.4 &nbsp;&nbsp;&nbsp;&nbsp;  Convenções, termos e abreviações </h3>
<p>
Para evitar interpretações incorretas deste documento, algumas convenções e termos específicos são descritos a seguir:
</p>

<table align="center">
  <tr>
    <td>RPA</td>
    <td>Automação robótica de processos</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>
   <tr>
    <td></td>
    <td></td>
  </tr>
</table>

<h3> 1.4.1 &nbsp;&nbsp;&nbsp;&nbsp; Identificação dos Requisitos </h3>
<p>
Cada requisito será unicamente identificado no formato [tipoRequisito.numero]. Para requisitos funcionais, o código do tipo de requisito será RF, e para requisitos não funcionais, RNF. Um número será assinalado a cada requisito de forma incremental, na ordem que forem mencionados neste documento.
</p>

<h3> 1.4.2 &nbsp;&nbsp;&nbsp;&nbsp; Prioridade dos Requisitos </h3>
<p>
Foram adotadas as seguintes denominações para estabelecer a prioridade dos requisitos: essencial, importante e desejável. </br>
<b>Essencial:</b> é o requisito sem o qual o sistema não entra em funcionamento, ou seja, são requisitos imprescindíveis tendo que ser implementados impreterivelmente.</br> 
<b>Importante:</b> é o requisito sem o qual o sistema entra em funcionamento, mas de maneira insatisfatória, ou seja, devem ser implementados, mas se não forem, o sistema poderá ser implantado e usado mesmo assim.</br>
<b>Desejável:</b> é o requisito que não compromete as funcionalidades básicas do sistema, podendo funcionar de forma satisfatória sem ele, ou seja, são requisitos que podem ser deixados para versões posteriores do sistema, caso não haja tempo hábil para implementá-los na versão que está sendo especificada. 	
</p>
</br></br>
<h3> 1.5 &nbsp;&nbsp;&nbsp;&nbsp; Referências</h3>  
<p>
&nbsp;&nbsp;&nbsp; N/D
</p>

<h3> 1.5 &nbsp;&nbsp;&nbsp;&nbsp; Visão Geral </h3>  
<p>	
Este documento está organizado da seguinte forma:
</p>
<ol>
  <ul>
	  <li> A seção 1 apresentou uma introdução ao documento de requisitos e ao sistema sendo especificado; </li>
	  <li> A seção 2 apresenta uma descrição geral do sistema;</li>
	  <li>A seção 3 apresenta as definições dos requisitos funcionais e não-funcionais do sistema;</li>
	  <li>A seção 4 apresenta o diagrama de casos de uso do sistema, bem como as descrições dos casos de uso definidos;</li>
  </ul>
</ol>


<br>
<h2 align="right">2 - Descrição geral</h2>

<h3> 2.1 &nbsp;&nbsp;&nbsp;&nbsp; Usuários do Sistema </h3>  
<p>	
<b>Usuário: </b>Tem acesso a funções do sistema (exemplo: gestão,  faturamento, fornecedores, indicadores entre outros).</p>

<p><b>Administrador: </b>Tem acesso ao painel administrativo e aos logs do sistema.</p>

<h3> 2.2 &nbsp;&nbsp;&nbsp;&nbsp; Abrangência e sistemas similares </h3>  
<p>
<b>Abrangência:</b>  
O sistema terá como objetivo carregar, visualizar e processar informações estratégicas do Itaú.
</p>

<b>Sistemas similares:</b><br>
<i>Portal. </i></br>
<i>Aplicações de RPA.</i></br>
<i>Bots.</i></br>


<h3> 2.3 &nbsp;&nbsp;&nbsp;&nbsp; Suposições e dependências </h3>  
<p>
As seguintes suposições são válidas no decorrer do desenvolvimento do sistema sendo especificado:</p>

<ol>
  <ul>
	  <li> O cliente está responsável pela aquisição de infraestrutura necessária em seu ambiente de produção; </li>
  </ul>
</ol>


<br><br>
<h2 align="right">3 - Requisitos do Software </h2>

<h3> 3.1 &nbsp;&nbsp;&nbsp;&nbsp; Requisitos Funcionais </h3>  	

<b>[RF01]</b> Cadastro de Usuários
O sistema deverá ter um formulário para cadastro de novos usuários.

<b>[RF02]</b> Login
O sistema deverá mostrar informações apenas para usuários que fizerem login com suas credenciais de acesso.

<b>[RF03]</b> Logoff
O sistema deverá encerrar a sessão do usuário atual.


<h3> 3.2 &nbsp;&nbsp;&nbsp;&nbsp; Requisitos Não-funcionais </h3>  
<p>
	Os requisitos que descrevem os aspectos não-funcionais do sistema são apresentados a seguir:
</p>

		
<h3> 3.2.1 &nbsp;&nbsp;&nbsp;&nbsp; Requisitos de Segurança </h3>  

<table>
    <caption>Requisitos de Segurança</caption>
    <thead>
        <tr>
            <th>Ident.</th>
            <th scope="col">Descrição</th>
	    <th scope="col">Casos de uso relacionados</th> 
        </tr>
    </thead>
    <tbody>
        <tr>
            <th scope="row">RNF/SEG-01</th>
            <td scope="row"> O usuário autorizado deverá efetuar login para poder realizar as operações no sistema. 	</td>
            <td scope="row"> </td>
        </tr>
    </tbody>
</table>



<h3> 3.2.2 &nbsp;&nbsp;&nbsp;&nbsp; Requisitos de Interface </h3>  

<table>
    <caption>Requisitos de Interface</caption>
    <thead>
        <tr>
            <th>Ident.</th>
            <th scope="col">Descrição</th>
	    <th scope="col">Casos de uso relacionados</th> 
        </tr>
    </thead>
    <tbody>
        <tr>
            <th scope="row">RNF/INT-01</th>
            <td scope="row"> O sistema deve ter uma interface amigável, de fácil utilização, ou seja, auto explicável. 	</td>
            <td scope="row"> </td>
        </tr>
    </tbody>
</table>

<h3> 3.2.3 &nbsp;&nbsp;&nbsp;&nbsp; Requisitos de Operacionais </h3>  
	
<table>
    <caption>Requisitos de Interface</caption>
    <thead>
        <tr>
            <th>Ident.</th>
            <th scope="col">Descrição</th>
	    <th scope="col">Casos de uso relacionados</th> 
        </tr>
    </thead>
    <tbody>
        <tr>
            <th scope="row">RNF/OPE-01</th>
            <td scope="row"> O sistema deve ser desenvolvido em C#. </td>
            <td scope="row"> </td>
        </tr>
	 <tr>
            <th scope="row">RNF/OPE-02</th>
            <td scope="row"> O sistema deverá ter uma arquitetura de microsserviços. 	</td>
            <td scope="row"> </td>
        </tr>
	 <tr>
            <th scope="row">RNF/OPE-03</th>
            <td scope="row"> A camada de aplicação para web deverá ser compatível com browser do Google Chrome.</td>
            <td scope="row"> </td>
        </tr>
    </tbody>
</table>
		
<h3> 3.2.4 &nbsp;&nbsp;&nbsp;&nbsp; Requisitos de Confiabilidade </h3> 
		
<table>
    <caption>Requisitos de Interface</caption>
    <thead>
        <tr>
            <th>Ident.</th>
            <th scope="col">Descrição</th>
	    <th scope="col">Casos de uso relacionados</th> 
        </tr>
    </thead>
    <tbody>
        <tr>
            <th scope="row">RNF/CON-01</th>
            <td scope="row"> O sistema deverá  armazenar os logs. 	</td>
            <td scope="row"> </td>
        </tr>
    </tbody>
</table>	
<br>
		
<h2 align="right"> 4 - Casos de uso</h2>
<h3> 4.1 &nbsp;&nbsp;&nbsp;&nbsp; Diagrama de casos de uso </h3> 
<p>
O diagrama de casos de uso, expresso em UML (Unified Modeling Language), expressa os requisitos funcionais do sistema na forma de casos de uso. Segundo o RUP (Rational Unified Process), para cada requisito funcional tem-se um caso de uso. A descrição textual detalhada dos requisitos funcionais, seus fluxos de atividades e requisitos não funcionais associados pode ser encontrada na próxima seção. Na figura abaixo mostramos a representação gráfica em UML dos casos de uso do sistema.		
</p>

<center><img src="https://i.ibb.co/bBcb1JR/image.png"></center>
		
<h3> 4.2 &nbsp;&nbsp;&nbsp;&nbsp; Descrição dos casos de uso </h3> 



<table>
    <caption>[CDU-01]</caption>
    <thead>
	 <tr>
		 <th> CDU </th>
	</tr>
        <tr>
            <th>Nome:</th>
            <th scope="col">Atores:</th>
	    <th scope="col"> Prioridade: </th> 
	    <th scope="col"> Requisitos associados: </th> 
	    <th scope="col"> Entradas e pré-condições: </th> 
		
		
		
        </tr>
    </thead>
    <tbody>
        <tr>
            <th scope="row">Realizar atividades </th>
            <td scope="row"> Usuário </td>
            <td scope="row"> Essencial </td>
            <td scope="row"> [RNF/SEG-01] </td>
        </tr>
    </tbody>
</table>












O usuário deverá executar a aplicação.
Saídas e pós-condições:
O usuário consegue realizar as atividades.
Fluxos de eventos
Fluxo principal:
O usuário inicia uma sessão no sistema.
O usuário escolhe a opção faturamento.
O usuário pode visualizar o faturamento.




<br>
<h2 align="right"> 5 - CLASSE</h2>
<h3> 5.1 &nbsp;&nbsp;&nbsp;&nbsp; Diagrama de Classes </h3> 
<center><img src="https://i.ibb.co/JFYmSCY/class-users-auth-v3.png"></center>




> Status: Developing 
