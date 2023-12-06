# Plano de Testes de Usabilidade

1. Objetivos.

Melhorias na plataforma, proporcionando a melhor experiência possível ao usuário. 

Minimizar e corrigir erros não notados.

Perceber as maiores necessidades e frustrações dos usuários. 

Otimização de tempo ao realizar atividades.

2. Dos critérios que serão utilizados para a seleção dos participantes.
   
Pessoas que se encaixem nas personas elaboradas. Encontradas na Internet, incluídas digitalmente, por meio de grupos que envolvam o tema e assuntos relacionados. 

3. Dos procedimentos a serem adotados pelos condutores de teste.
   
Os procedimentos serão realizados por meio de Testes Não Moderados de Usabilidade.  

4. Das tarefas a serem realizadas, dos dados a serem encontrados.
   
Criar um cenário-tarefa > Observar o comportamento e desenvoltura do usuário > Analisar tempo gasto para realizar tarefas pré-definidas, assim como constatar número de erros e áreas da tela mais usadas.

5. Das ordens de execução das tarefas e das etapas sessão de teste, recursos demandados, coletadas. 

A ser melhorado diante dos exemplos propostos posteriormente*

| **Caso de Teste** 	| **CTU-01 – Cadastrar perfil** 	|
|:---:	|:---:	|
|	Usuário 	| Todos os usuários |
| Objetivo do Teste 	| Avaliar a tela de cadastro de novo usuário |
| Passos 	| - Acessar o navegador na tela inicial <br> - Clicar em "Entrar" <br> - Acessar o navegador na tela login <br>- Clicar em "Novo Cadastro" <br> - Preencher os campos obrigatórios (e-mail, nome, data de nascimento,endereco, login, senha, confirmação de senha, tipo, telefone, RG, CPF, ) <br> - Clicar em "Salvar" |
|  	|  	|
| **Caso de Teste** 	| **CT-02 – Gerenciar produtos** 	|
|	Requisito Associado 	| RF-002 - A aplicação deve ter, na página principal do perfil do empreendedor, a página de "Gerenciar produtos". Dentre dessa página com as funcionalidades "registrar", "editar", "deletar" e "Quantidade" para que os usuários empreendedores consigam gerenciar seus produtos no seu perfil. |
| Objetivo do Teste 	| Verificar se o usuário consegue se cadastrar os produtos no seu perfil na aplicação. |
| Passos 	| - Acessar o navegador <br> - Informar o endereço do site https://ecoempreendedor.com/src/index.html<br> - Preencher os campos e-mail e senha <br>  - Clicar em "login"  <br> - clicar em "Gerenciar produtos"|
|Critério de Êxito | O usuário empreendedor consegue gerenciar produtos com sucesso. |
|  	|  	|
| **Caso de Teste** 	| **CT-03 – Visualizar os comentários** 	|
|	Requisito Associado 	| RF-003 - A aplicação deve permitir os usuários (os empreendedores e os clientes) consigam visualizar os comentários na páginas dos produtos. |
| Objetivo do Teste 	| Verificar se o usuário consegue visualizar a seção de comentários nas página dos produtos. |
| Passos 	| - Acessar o navegador <br> - Informar o endereço do site https://ecoempreendedor.com/src/index.html<br> - Preencher os campos e-mail e senha <br>  - Clicar em "login"  <br> - clicar em "Produtos" <br> - escolher um produto e clicar neste|
|Critério de Êxito | O usuário consegue visualizar a seção de comentários na página do produto escolhido com sucesso. |
|  	|  	|
| **Caso de Teste** 	| **CT-04 – Enviar comentários** 	|
|	Requisito Associado 	| RF-004 - A aplicação deve permitir os usuários (tanto empreendedores e quanto os clientes) possam interagir na seção de comentários na páginas dos produtos. |
| Objetivo do Teste 	| Verificar se o usuário consegue fazer um comentário na a seção de comentários nas página dos produtos. |
| Passos 	| - Acessar o navegador <br> - Informar o endereço do site https://ecoempreendedor.com/src/index.html<br> - Preencher os campos e-mail e senha <br>  - Clicar em "login"  <br> - clicar em "Produtos" <br> - escolher um produto e clicar <br> - preencher no campo do "comentário" <br> - clicar "Enviar"|
|Critério de Êxito | O usuário consegue fazer um comentário na seção de comentários na página do produtos escolhido com sucesso. |
|  	|  	|
| **Caso de Teste** 	| **CT-05 – Visualizar a informação "vegano" ou "não vegano"** 	|
|Requisito Associado | RF-005	- A aplicação deve apresentar a informação "vegano" ou "não vegano" nas páginas dos produtos |
| Objetivo do Teste 	| Verificar se o usuário cliente consegue visualizar a informação. |
| Passos 	| - Acessar o navegador <br> - Informar o endereço do site https://ecoempreendedor.com/src/index.html<br> - Clicar no botão "Entrar" <br> - Preencher o campo de e-mail <br> - Preencher o campo da senha <br> - Clicar em "Login" <br> - Clicar em "Produtos"<br> - escolher um e clicar|
|Critério de Êxito | O usuário cliente consegue visualizar as informações "vegano" ou "não vegano" na página do produto escolhido com sucesso. E o usuário empreendedor consegue escolher entre as opções "vegano" ou "não vegano" ao registrar o produto no sistema com sucesso.|
|  	|  	|
| **Caso de Teste** 	| **CT-06 – Pesquisar os produtos** 	|
|Requisito Associado | RF-006	- A aplicação deve permitir que os usuários clientes consigam pesquisar os produtos por diferentes critérios |
| Objetivo do Teste 	| Verificar se o usuário cliente consegue pesquisar visualizar, adicionar e excluir os produtos no carrinhos de compras. |
| Passos 	| - Acessar o navegador <br> - Informar o endereço do site https://ecoempreendedor.com/src/index.html<br> - Clicar no botão "Entrar" <br> - Preencher o campo de e-mail <br> - Preencher o campo da senha <br> - Clicar em "Login" <br> - Clicar em "Produtos"<br> - Aparece as opções "Cabelo", "Pele" e "Acessórios"|
|Critério de Êxito | O usuário consegue visualizar apenas os produtos referente à opção selecionada  com sucesso. |
|  	|  	|
| **Caso de Teste** 	| **CT-07 – Gerenciar o carrinhos de compras** 	|
|Requisito Associado | RF-007	- A aplicação deve permitir que os usuários clientes consigam visualizar, adicionar e excluir os produtos no carrinhos de compras|
| Objetivo do Teste 	| Verificar se o usuário cliente consegue pesquisar e filtrar por diferentes critérios. |
| Passos 	| - Acessar o navegador <br> - Informar o endereço do site https://ecoempreendedor.com/src/index.html<br> - Clicar no botão "Entrar" <br> - Preencher o campo de e-mail <br> - Preencher o campo da senha <br> - Clicar em "Login" <br> - Clicar em "Produtos"<br> - clicar em "adicionar no carrinho" <br> - clicar em "carrinho de compras"<br> - selecionar a quantidade <br> - clicar em "Excluir" <br> - Voltar para a página de compras|
|Critério de Êxito | O usuário consegue visualizar, adicionar e excluir os produtos no carrinhos de compras e voltar para a página dos produtos com sucesso.|
|  	|  	|
| **Caso de Teste** 	| **CT-08 – Finalizar pedido** 	|
|Requisito Associado | RF-008	- A aplicação deve ter a funcionalidade "Finalizar pedido" no carrinhos de compras|
| Objetivo do Teste 	| Verificar se o usuário cliente consegue pesquisar e filtrar por diferentes critérios. |
| Passos 	| - Acessar o navegador <br> - Informar o endereço do site https://ecoempreendedor.com/src/index.html<br> - Clicar no botão "Entrar" <br> - Preencher o campo de e-mail <br> - Preencher o campo da senha <br> - Clicar em "Login" <br> - Clicar em "Produtos"<br> - clicar em "adicionar no carrinho" <br> - clicar em "carrinho de compras"<br> - selecionar a quantidade <br> - clicar em "Finalizar pedido" <br> - Aparecer o preço final|
|Critério de Êxito | O usuário consegue finalizar o pedido e receber o preço final com sucesso. |
|  	|  	|
| **Caso de Teste** 	| **CT-09 – Visualizar o número atualizado da quantidade de produtos disponíveis** 	|
|Requisito Associado | RF-009	- A aplicação deve apresentar uma atualização do número referente a quantidade de produtos disponíveis para o usuário empreendedor. Toda vez que um produto for vendido o sistema precisa atualizar a quantidade|
| Objetivo do Teste 	| Verificar se o usuário empreendedor consegue visualizar o número atualizado da quantidade de produtos disponíveis. |
| Passos 	| - Acessar o navegador <br> - Informar o endereço do site https://ecoempreendedor.com/src/index.html<br> - Preencher os campos e-mail e senha <br>  - Clicar em "login"  <br> - clicar em "Gerenciar produtos"<br> - clicar em "Quantidade" <br> - Visualizar a quantidade atualizada após a venda|
|Critério de Êxito | O usuário consegue finalizar o pedido e receber o preço final com sucesso. |
|  	|  	|
| **Caso de Teste** 	| **CT-10 – Visualizar o relatório de vendas** 	|
|Requisito Associado | RF-010	- A aplicação deve apresentar um relatório de vendas para o usuário Empreendedor|
| Objetivo do Teste 	| Verificar se o usuário empreendedor consegue visualizar  número atualizado da quantidade de produtos disponíveis. |
| Passos 	| - Acessar o navegador <br> - Informar o endereço do site https://ecoempreendedor.com/src/index.html<br> - Preencher os campos e-mail e senha <br>  - Clicar em "login"  <br> - clicar em "Relatório" <br> - Visualizar relatório de vendas|
|Critério de Êxito | O usuário Empreendedor consegue finalizar visualizar relatório de vendas com sucesso. |
|  	|  	|
| **Caso de Teste** 	| **CT-11 – Teste de responsividade** 	|
|Requisito Associado | RNF-01	- A aplicação deve ter responsividade|
| Objetivo do Teste 	| Verificar as páginas renderizarem bem em uma variedade de dispositivos e tamanhos de janela ou tela do mínimo ao máximo. |
| Passos 	| - Acessar o navegador <br> - Informar o endereço do site https://ecoempreendedor.com/src/index.html<br> - Repetir o processo em diferentes tamanhos de dispositivos|
|Critério de Êxito | O usuário consegue visualizar as páginas redenrizadas em diferentes tamanhos de telas com sucesso. |
|  	|  	|
| **Caso de Teste** 	| **CT-12 – Teste de integridade e segurança de dados** 	|
|Requisito Associado | RNF-02	- A aplicação estar dentro das normas da LGPD|
| Objetivo do Teste 	| Verificar se dados foram registrados corretamente no banco de dados após o cadastro do usuário e o registro do produto. Também verificar a exclusão dos dados no Banco de dados após os usuários exluírem os produtos, e alteração dos dados após os usuários atualizarem o perfi e depois da venda a atualiação da quantidade. |
| Passos 	| - Verificar os dados no Banco de dados após o cadastro de usuário<br> - Verificar os dados no Banco de dados após o registro de produto <br> -Verificar os dados no Banco de dados após exclusão dos produtos <br> - Verificar os dados usuários no Banco de dados após a alteração do perfil <br> -Verificar os dados de quantidade de produtos no Banco de dados após as vendas |
|Critério de Êxito | O usuário consegue visualizar os dados atualizado com sucesso. |
|  	|  	|
| **Caso de Teste** 	| **CT-13 – Efetuar login** 	|
|Requisito Associado | RF-03	- A aplicação deve possuir opção de fazer login, sendo o login o endereço de e-mail. |
| Objetivo do Teste 	| Verificar se o usuário consegue realizar login. |
| Passos 	| - Acessar o navegador <br> - Informar o endereço do site https://ecoempreendedor.com/src/index.html<br> - Clicar no botão "Entrar" <br> - Preencher o campo de e-mail <br> - Preencher o campo da senha <br> - Clicar em "Login" |
|Critério de Êxito | O login foi realizado com sucesso. |
|  	|  	|
| **Caso de Teste** 	| **CT-14 – Seção de comentários** 	|
|Requisito Associado | RNF-04	- A aplicação deve possuir uma Seção de comentários nas páginas de cada produto |
| Objetivo do Teste 	| Verificar se cada produto tem uma seção de comentário com o campo que permite o usuário preencher e enviar o comentário. |
| Passos 	| - Acessar o navegador <br> - Informar o endereço do site https://ecoempreendedor.com/src/index.html<br> - Clicar no botão "Entrar" <br> - Preencher o campo de e-mail <br> - Preencher o campo da senha <br> - Clicar em "Login" <br> - Escolher um produto e clicar neste<br> - Na página do produto visualizar a Seção de comentários <br> - Clicar em no campo de comentário e preencher <br> - Enviar o comentário <br> - Visualizar o comentário.|
|Critério de Êxito | O comentário foi realizado com sucesso. |
