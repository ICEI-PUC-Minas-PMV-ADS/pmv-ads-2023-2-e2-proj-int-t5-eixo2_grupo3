# Especificações do Projeto


## Personas

### Empreendedores

![image](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e2-proj-int-t5-eixo2_grupo3/assets/129327473/e08e40a8-656a-4627-a3c8-78d7147f582c)


**Nome:** Carolina Martins

**Sexo:** Feminino

**Idade:** 35 anos

**Localização:** Belo Horizonte, Minas Gerais

**Ocupação:** Empreendedora na área de produtos naturais para cabelos.

**Qualificação:** Formada em Farmácia na Pontifícia Universidade Católica de Minas Gerais em 2015.

**História:** Vinda da periferia de Belo Horizonte, filha de uma faxineira e de um catador de recicláveis, Carolina cresceu observando as dificuldades financeiras dos pais, sempre valorizou todos os recursos dos pais e admirou o trabalho do pai junto ao meio ambiente. Apesar de todas as dificuldades conseguiu se formar na faculdade de Farmácia e hoje possui sua própria empresa de produtos naturais em barra para cabelos.

**Motivações:** Produzir cosméticos em barra visando a diminuição de embalagens plásticas no meio ambiente.

**Frustrações:** Pouca visibilidade em meio a tantos produtos industrializados já existentes de marcas conhecidas.

![image](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e2-proj-int-t5-eixo2_grupo3/assets/129327473/239e86b4-b6c6-49ee-bea6-48c64dddf55e)


**Nome:** Aurora Noronha

**Sexo:** Feminino

**Idade:** 26 anos

**Localização:** Tiradentes, Minas Gerais.

**Ocupação:** Empreendedora na área de produtos naturais para a pele.

**Qualificação:** Formada no Curso Superior de Tecnologia em Cosméticos pela Faculdade Oswaldo Cruz em 2021.

**História:** Vinda de uma família naturalista, cresceu no interior do estado em meio a natureza. Foi para São Paulo para fazer o curso de cosméticos, ao retornar para sua comunidade fundou uma marca de produtos naturais veganos para pele.

**Motivações:** Influenciar as pessoas a utilizar produtos naturais e veganos, pensando no bem estar do meio ambiente.

**Frustrações:** Pouca divulgação por morar no interior.

### Clientes

![image](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e2-proj-int-t5-eixo2_grupo3/assets/129327473/38495a32-1ff7-4d55-b952-e590784062bd)


**Nome:** Vanessa Fonseca.

**Sexo:** Feminino.

**Idade:** 21 anos.

**Localização:** Rio de Janeiro capital.

**Ocupação:** Estudante de curso superior.

**História:** Mora com os pais, com as crescentes mudanças no clima global vem cada vez mais se preocupando com as questões de sustentabilidade, com isso procurou colocar como uma meta para si mesmo usar produtos que sejam sustentáveis como uma forma de amenizar o impacto ambiental.

**Motivações:** Ajudar o meio ambiente utilizando produtos sustentáveis.

**Frustrações:** Dificuldade em encontrar os produtos.

![image](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e2-proj-int-t5-eixo2_grupo3/assets/129327473/fcde4ee4-c067-41aa-9de6-39bc026c6d57)


**Nome:** Roberta Madureira.

**Sexo:** Feminino.

**Idade:** 33 anos.

**Localização:** São Paulo capital.

**Ocupação:** Cabelereira.

**História:** Possui seu próprio salão, vem apostando na sustentabilidade como uma forma de atrair um público novo que pensa de forma consciente para seu comércio, acredita que levantando essa bandeira pode agregar mais valor aos seus serviços e ao mesmo tempo ajuda o meio ambiente.

**Motivações:** Ajudar o meio ambiente e captar mais clientes com o mesmo pensamento.

**Frustrações:** Dificuldade em encontrar os produtos.


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário do sistema  | Registrar minhas tarefas           | Não esquecer de fazê-las               |
|Administrador       | Alterar permissões                 | Permitir que possam administrar contas |

Apresente aqui as histórias de usuário que são relevantes para o projeto de sua solução. As Histórias de Usuário consistem em uma ferramenta poderosa para a compreensão e elicitação dos requisitos funcionais e não funcionais da sua aplicação. Se possível, agrupe as histórias de usuário por contexto, para facilitar consultas recorrentes à essa parte do documento.

> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/)

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que o usuário cadastre tarefas | ALTA | 
|RF-002| Emitir um relatório de tarefas no mês   | MÉDIA |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser uma aplicação web responsiva | ALTA | 
|RNF-002| O sistema deve garantir que os dados sobre os empreendedores e os consumidores sejam armazenados dentros nas normas da LGPD |  ALTA | 
|RNF-003| O sistema deve permitir que todos os usuários cadastrados tenham acesso ao aplicativo pelo login e senha |  ALTA | 
|RNF-004| O sistema deve permitir os empreendedores cadastrarem os seus produtos |  ALTA | 
|RNF-005| O sistema deve permitir os consumidores colocarem os produtos selecionados em um carrinho de compras |  ALTA | 

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |


Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)

## Diagrama de Casos de Uso

O diagrama de casos de uso é o próximo passo após a elicitação de requisitos, que utiliza um modelo gráfico e uma tabela com as descrições sucintas dos casos de uso e dos atores. Ele contempla a fronteira do sistema e o detalhamento dos requisitos funcionais com a indicação dos atores, casos de uso e seus relacionamentos. 

As referências abaixo irão auxiliá-lo na geração do artefato “Diagrama de Casos de Uso”.

> **Links Úteis**:
> - [Criando Casos de Uso](https://www.ibm.com/docs/pt-br/elm/6.0?topic=requirements-creating-use-cases)
> - [Como Criar Diagrama de Caso de Uso: Tutorial Passo a Passo](https://gitmind.com/pt/fazer-diagrama-de-caso-uso.html/)
> - [Lucidchart](https://www.lucidchart.com/)
> - [Astah](https://astah.net/)
> - [Diagrams](https://app.diagrams.net/)
