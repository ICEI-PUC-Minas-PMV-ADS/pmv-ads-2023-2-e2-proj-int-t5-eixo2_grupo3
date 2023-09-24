# Plano de Testes de Software

<span style="color:red">Pré-requisitos: <a href="2-Especificação do Projeto.md"> Especificação do Projeto</a></span>, <a href="3-Projeto de Interface.md"> Projeto de Interface</a>

Apresente os cenários de testes utilizados na realização dos testes da sua aplicação. Escolha cenários de testes que demonstrem os requisitos sendo satisfeitos.

Não deixe de enumerar os casos de teste de forma sequencial e de garantir que o(s) requisito(s) associado(s) a cada um deles está(ão) correto(s) - de acordo com o que foi definido na seção "2 - Especificação do Projeto". 

Por exemplo:
 
| **Caso de Teste** 	| **CT-01 – Cadastrar perfil** 	|
|:---:	|:---:	|
|	Requisito Associado 	| RF-001 - A aplicação deve apresentar, na página principal, a funcionalidade de cadastro de usuários para que esses consigam criar e gerenciar seu perfil. |
| Objetivo do Teste 	| Verificar se o usuário consegue se cadastrar na aplicação. |
| Passos 	| - Acessar o navegador <br> - Informar o endereço do site https://ecoempreendedor.com/src/index.html<br> - Clicar em "Criar conta" <br> - Preencher os campos obrigatórios (e-mail, nome, sobrenome, celular, CPF, senha, confirmação de senha) <br> - Aceitar os termos de uso <br> - Clicar em "Confirmar" |
|Critério de Êxito | - O cadastro foi realizado com sucesso. |
|  	|  	|
|	Requisito Associado 	| RF-002 - A aplicação deve ter, na página principal do perfil do empreendedor, a página de "Gerenciar produtos". Dentre dessa página com as funcionalidades "registrar", "editar",  e "deletar" para que os usuários empreendedores consigam gerenciar seus produtos no seu perfil. |
| Objetivo do Teste 	| Verificar se o usuário consegue se cadastrar os produtos no seu perfil na aplicação. |
| Passos 	| - Acessar o navegador <br> - Informar o endereço do site https://ecoempreendedor.com/src/index.html<br> - Preencher os campos e-mail e senha <br>  - Clicar em "login"  <br> - clicar em "Gerenciar produtos"|
|Critério de Êxito | - O usuário empreendedor consegue abrir a página "gerenciar produtos" com sucesso. |
|  	|  	|
|	Requisito Associado 	| RF-003 - A aplicação deve permitir os usuários (tanto empreendedores e clientes) consigam visualizar os comentários na páginas dos produtos. |
| Objetivo do Teste 	| Verificar se o usuário consegue visualizar a seção de comentários nas página dos produtos. |
| Passos 	| - Acessar o navegador <br> - Informar o endereço do site https://ecoempreendedor.com/src/index.html<br> - Preencher os campos e-mail e senha <br>  - Clicar em "login"  <br> - clicar em "Produtos" <br> - escolher um produto e clicar|
|Critério de Êxito | - O usuário consegue visualizar a seção de comentários na página do produtos escolhido com sucesso. |
|  	|  	|
| Caso de Teste 	| CT-02 – Efetuar login	|
|Requisito Associado | RF-00Y	- A aplicação deve possuir opção de fazer login, sendo o login o endereço de e-mail. |
| Objetivo do Teste 	| Verificar se o usuário consegue realizar login. |
| Passos 	| - Acessar o navegador <br> - Informar o endereço do site https://adota-pet.herokuapp.com/src/index.html<br> - Clicar no botão "Entrar" <br> - Preencher o campo de e-mail <br> - Preencher o campo da senha <br> - Clicar em "Login" |
|Critério de Êxito | - O login foi realizado com sucesso. |

 
> **Links Úteis**:
> - [IBM - Criação e Geração de Planos de Teste](https://www.ibm.com/developerworks/br/local/rational/criacao_geracao_planos_testes_software/index.html)
> - [Práticas e Técnicas de Testes Ágeis](http://assiste.serpro.gov.br/serproagil/Apresenta/slides.pdf)
> -  [Teste de Software: Conceitos e tipos de testes](https://blog.onedaytesting.com.br/teste-de-software/)
> - [Criação e Geração de Planos de Teste de Software](https://www.ibm.com/developerworks/br/local/rational/criacao_geracao_planos_testes_software/index.html)
> - [Ferramentas de Test para Java Script](https://geekflare.com/javascript-unit-testing/)
> - [UX Tools](https://uxdesign.cc/ux-user-research-and-user-testing-tools-2d339d379dc7)
