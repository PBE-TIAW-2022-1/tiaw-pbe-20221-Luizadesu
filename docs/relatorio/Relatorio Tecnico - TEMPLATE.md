# Informações do Projeto
`TÍTULO DO PROJETO`  

Conversor de Unidades

`CURSO` 

Sistemas De Informação

## Participantes

> Arthur Gomes Murta
> Luísa Machado Antunes Santos
> Luiza Dutra Carvalho
> Marcos Filipe Dutra de Oliveira
> Riquelme Augusto de Oliveira
> Rodrigo Nogueira Duarte
> Thales Cançado Costa


> Inclua a lista dos membros da equipe com seus nomes completos.
>
> Os membros do grupo são: 
> - Fulano da Silva
> - Ciclano Albuquerque

# Estrutura do Documento

- [Informações do Projeto](#informações-do-projeto)
  - [Participantes](#participantes)
- [Estrutura do Documento](#estrutura-do-documento)
- [Introdução](#introdução)
  - [Problema](#problema)
  - [Objetivos](#objetivos)
  - [Justificativa](#justificativa)
  - [Público-Alvo](#público-alvo)
- [Especificações do Projeto](#especificações-do-projeto)
  - [Personas e Mapas de Empatia](#personas-e-mapas-de-empatia)
  - [Histórias de Usuários](#histórias-de-usuários)
  - [Requisitos](#requisitos)
    - [Requisitos Funcionais](#requisitos-funcionais)
    - [Requisitos não Funcionais](#requisitos-não-funcionais)
  - [Restrições](#restrições)
- [Projeto de Interface](#projeto-de-interface)
  - [User Flow](#user-flow)
  - [Wireframes](#wireframes)
- [Metodologia](#metodologia)
  - [Divisão de Papéis](#divisão-de-papéis)
  - [Ferramentas](#ferramentas)
  - [Controle de Versão](#controle-de-versão)
- [**############## SPRINT 1 ACABA AQUI #############**](#-sprint-1-acaba-aqui-)
- [Projeto da Solução](#projeto-da-solução)
  - [Tecnologias Utilizadas](#tecnologias-utilizadas)
  - [Arquitetura da solução](#arquitetura-da-solução)
- [Avaliação da Aplicação](#avaliação-da-aplicação)
  - [Plano de Testes](#plano-de-testes)
  - [Ferramentas de Testes (Opcional)](#ferramentas-de-testes-opcional)
  - [Registros de Testes](#registros-de-testes)
- [Referências](#referências)


# Introdução

## Problema

Em nosso Design Thinking, realizamos o mapeamento da persona e do público alvo, o que nos auxiliou com nosso projeto. Procuramos resolver o problema dos estudantes, principalmente, em relação a ausência de plataformas online populares de conversão e ensino do mesmo no mercado, já que muitas vezes eles precisam visitar diversos sites para conseguir realizar diferentes conversões. Além disso, também nos focamos em melhorar a forma de ensino atual, para que seja mais objetiva e acolhedora, usando de videos curtos e objetivos, motivando o usuário a colocar em prática o conteúdo, já que atualmente as plataformas existentes não se preocupam em ensinar e motivar o estudante a aprender. 

> Nesse momento você deve apresentar o problema que a sua aplicação deve
> resolver. No entanto, não é a hora de comentar sobre a aplicação.
> Descreva também o contexto em que essa aplicação será usada, se
> houver: empresa, tecnologias, etc. Novamente, descreva apenas o que de
> fato existir, pois ainda não é a hora de apresentar requisitos
> detalhados ou projetos.
>
> Nesse momento, o grupo pode optar por fazer uso
> de ferramentas como Design Thinking, que permite um olhar de ponta a
> ponta para o problema.
>
> **Links Úteis**:
> - [Objetivos, Problema de pesquisa e Justificativa](https://medium.com/@versioparole/objetivos-problema-de-pesquisa-e-justificativa-c98c8233b9c3)
> - [Matriz Certezas, Suposições e Dúvidas](https://medium.com/educa%C3%A7%C3%A3o-fora-da-caixa/matriz-certezas-suposi%C3%A7%C3%B5es-e-d%C3%BAvidas-fa2263633655)
> - [Brainstorming](https://www.euax.com.br/2018/09/brainstorming/)

## Objetivos

A finalidade do nosso trabalho é ofertar ao público uma plataforma online, de fácil utilização e eficiente de conversão de diversas medidas, e que conte com uma função de “faça você mesmo”, como um tutorial, dando além da informação direta que o usuário deseja, a opção também de entender a conversão e aprender a fazê-la. Com isso, aprofundaremos nossa prática em proporcinar ao usuário diversas conversões em uma página da internet com video aulas disponíveis, para que eles possam aprender  e aprofundar seu conhecimento no assunto desejado.

> Aqui você deve descrever os objetivos do trabalho indicando que o
> objetivo geral é desenvolver um software para solucionar o problema
> apresentado acima. Apresente também alguns (pelo menos 2) objetivos
> específicos dependendo de onde você vai querer concentrar a sua
> prática investigativa, ou como você vai aprofundar no seu trabalho.
> 
> **Links Úteis**:
> - [Objetivo geral e objetivo específico: como fazer e quais verbos utilizar](https://blog.mettzer.com/diferenca-entre-objetivo-geral-e-objetivo-especifico/)

## Justificativa

Por meio de entrevistas realizadas, nosso trabalho foi incentivado pela necessidade dos estudantes, em geral, de realizar conversões de diversas grandezas, e que possa ofertar em uma única plataforma, essas necessidades. Mas, mais que isso, possa proporcionar formas do estudante aprender a realizá-las, através de video aulas curtas e objetivas, que possam despertar a vontade de aprender e a utilizar as conversões no dia a dia. Nossa plataforma também se destina a pessoas que possam estar interesadas ou com alguma dúvida em relação a realização de conversões.

> Descreva a importância ou a motivação para trabalhar com esta aplicação
> que você escolheu. Indique as razões pelas quais você escolheu seus
> objetivos específicos ou as razões para aprofundar em certos aspectos
> do software.
> 
> O grupo de trabalho pode fazer uso de questionários, entrevistas e
> dados estatísticos, que podem ser apresentados, com o objetivo de
> esclarecer detalhes do problema que será abordado pelo grupo.
>
> **Links Úteis**:
> - [Como montar a justificativa](https://guiadamonografia.com.br/como-montar-justificativa-do-tcc/)

## Público-Alvo

Com a realização das entrevistas, foi constatado que quem faria mais uso de tal ferramenta de conversão, seriam estudantes, e pessoas com dúvidas no cotidiano, e que essas pessoas, em suma preferem conteúdo de ensino em formato de vídeos curtos e diretos, objetivos, logo a plataforma Converta é focada nesse público.

Gênero: masculino e feminino
Faixa etária: entre 12 e 24 anos, principalmente
Escolaridade: ensino fundamental, médio e graduando
Renda: entre 1 e 6 salários mínimos
Classe social: classe baixa e média
Localização: Brasil
Hábitos de consumo: médio e elevado

> Descreva quem serão as pessoas que usarão a sua aplicação indicando os
> diferentes perfis. O objetivo aqui não é definir quem serão os
> clientes ou quais serão os papéis dos usuários na aplicação. A ideia
> é, dentro do possível, conhecer um pouco mais sobre o perfil dos
> usuários: conhecimentos prévios, relação com a tecnologia, relações
> hierárquicas, etc.
>
> Adicione informações sobre o público-alvo por meio de uma descrição
> textual, ou diagramas de personas, mapa de stakeholders, ou como o
> grupo achar mais conveniente.
> 
> **Links Úteis**:
> - [Público-alvo: o que é, tipos, como definir seu público e exemplos](https://klickpages.com.br/blog/publico-alvo-o-que-e/)
> - [Qual a diferença entre público-alvo e persona?](https://rockcontent.com/blog/diferenca-publico-alvo-e-persona/)
 
# Especificações do Projeto  ...............

1- Deve converter medidas corretamente
2-Ser capaz de identificar possíveis erros de digitação do usuário e sugerir uma correção
3-Exibir uma página com o resultado e tutorial após a solicitação do usuário
4-O personagem interativo Sérgio deve seguir um script dentro do contexto
5-Precisa ter as fórmulas de conversão dentro dos dados
6-Deve exibir o layout do site de acordo com o planejado
7-Armazenar os dados de logins de cada usuário, para manter o histórico de buscas

> Apresente uma visão geral do que será abordado nesta parte do
> documento, enumerando as técnicas e/ou ferramentas utilizadas para
> realizar a especificações do projeto

## Personas e Mapas de Empatia

Nossa persona será o Sergio, um professor de matématica, de 35 anos, negro, que irá ajudar os usuários, alunos e pessoas que precisarem realizar alguma conversão, a realizar as conversões desejadas, e guia-lás pelo site, ensinando a usa-lo e a como converter as unidades desejadas. A aparência de nossa persona será como a imagem do Wireframe. Abaixo realizamos uma série de perguntas para mapearmos nossa persona: 

No que trabalha: é professor
Qual seu lazer preferido: ler livros e jogar xadrez
O que faz nas horas livres: assiste documentários e estuda matemática e conversões
Onde costuma comprar: livrarias
Quais são as suas redes sociais preferidas: instagram e twitter
Que tipo de conteúdo consome na internet: conteúdos relacionados a exatas e comunicação
Quais blogs e sites visita: globo notícias e scientific american
Objetivo: ajudar os estudantes a realizar as conversões de maneira rápida e objetiva
Dificuldades: oferecer a todos os estudantes e interesados, uma educação de qualidade e objetiva que possa aproximar o estudante e despertar o desejo em aprender

Thales Cançado e Henrique (Desenvolvedor Front End) 
Arthur e Marcos Filipe (Desenvolvedor Back End) 
Luisa Machado e Luiza (Analista de Negócios) 
Rodrigo Duarte (Desenvolvedor Front End) 
Riquelme Oliveira (Designer)


> Relacione as personas identificadas no seu projeto e os respectivos mapas de empatia. Lembre-se que 
> você deve ser enumerar e descrever precisamente e de forma
> personalizada todos os principais envolvidos com a solução almeja. 
> 
> Para tanto, baseie-se tanto nos documentos disponibilizados na disciplina
> e/ou nos seguintes links:
>
> **Links Úteis**:
> - [Persona x Público-alvo](https://flammo.com.br/blog/persona-e-publico-alvo-qual-a-diferenca/)
> - [O que é persona?](https://resultadosdigitais.com.br/blog/persona-o-que-e/)
> - [Rock Content](https://rockcontent.com/blog/personas/)
> - [Hotmart](https://blog.hotmart.com/pt-br/como-criar-persona-negocio/)
> - [Mapa de Empatia](https://resultadosdigitais.com.br/blog/mapa-da-empatia/)
> - [Como fazer um mapa de empatia - Vídeo](https://www.youtube.com/watch?v=JlKHGpVoA2Y)
> 
> 
> **Exemplo de Persona**
> 
> ![Exemplo de Persona](imaages/../images/persona.png)
> 
> Fonte: [Como criar uma persona para o seu negócio](https://raissaviegas.com.br/como-criar-uma-persona/)


## Histórias de Usuários .

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `Professor de matématica`| QUERO/PRECISO ... `Realizar as conversões e ensinar os úsuarios a realizalás` |PARA ... `Mostrar os resultados e ensinar as pessoas a faze-las sozinha no futuro`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário do sistema  | Registrar minhas tarefas           | Não esquecer de fazê-las               |
|Administrador       | Alterar permissões                 | Permitir que possam administrar contas |

> Apresente aqui as histórias de usuário que são relevantes para o
> projeto de sua solução. As Histórias de Usuário consistem em uma
> ferramenta poderosa para a compreensão e elicitação dos requisitos
> funcionais e não funcionais da sua aplicação. Se possível, agrupe as
> histórias de usuário por contexto, para facilitar consultas
> recorrentes à essa parte do documento.
>
> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)

## Requisitos .

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que o usuário cadastre tarefas | ALTA | 
|RF-002| Emitir um relatório de tarefas no mês   | MÉDIA |

..................................................

1- Deve converter medidas corretamente
2-Ser capaz de identificar possíveis erros de digitação do usuário e sugerir uma correção
3-Exibir uma página com o resultado e tutorial após a solicitação do usuário
4-O personagem interativo Sérgio deve seguir um script dentro do contexto
5-Precisa ter as fórmulas de conversão dentro dos dados
6-Deve exibir o layout do site de acordo com o planejado
7-Armazenar os dados de logins de cada usuário, para manter o histórico de buscas


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s |  BAIXA | 
...............................................

1- Deve ser um sistema de confiablidade que preserve o usuário de quaisquer danos
2-Precisa estar disponível na rede a qualquer momento para alcançar máximo de pessoas
3- Deve ser um sistema ágil que atenda com rapidez a necessidade do usuário
4- Deve ser uma plataforma de fácil uso do usuário
5- Precisa ter o desempenho esperado
6- Precisa ter segurança de dados como nome, endereço de e-mail e dados de pagamento de contas pró


> Com base nas Histórias de Usuário, enumere os requisitos da sua
> solução. Classifique esses requisitos em dois grupos:
>
> - [Requisitos Funcionais (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
>   correspondem a uma funcionalidade que deve estar presente na
>   plataforma (ex: cadastro de usuário).
>
> - [Requisitos Não Funcionais (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
>   correspondem a uma característica técnica, seja de usabilidade,
>   desempenho, confiabilidade, segurança ou outro (ex: suporte a
>   dispositivos iOS e Android).
>
> Lembre-se que cada requisito deve corresponder à uma e somente uma
> característica alvo da sua solução. Além disso, certifique-se de que
> todos os aspectos capturados nas Histórias de Usuário foram cobertos.
> 
> **Links Úteis**:
> 
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)


## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |

Restrições do projeto:
1- Atualização em tempo real do valor das moedas pelo mundo;
2- Servidor que suporte um grande número de usuários;
3- Entrega do Google no topo do resultado das pesquisas;
4- Segurança de dados de todos os usuários;
5- Produção de tutorias e inserção na plataforma para todas as
conversões;
6- Custos envolvidos;
7- Escopo do projeto;
8- Prazo acelerado que pode impactar nas entregas;
9- Opiniões divergentes da equipe;
10- Disponibilização de todas as ferramentas necessárias;
11- Complexidade do algoritmo capaz de suprir as expectativas.


> Enumere as restrições à sua solução. Lembre-se de que as restrições
> geralmente limitam a solução candidata.
> 
> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)


# Projeto de Interface

Nossas interfaces foram elaboradas de forma simples, para que fosse acessivel a todos os usúarios, para que ele possa navegar rapidamente em todo o site, e que contasse com a ajuda de nossa persona, Sérgio. Todas os botões são intuitivos, quando o usuário clica em um botão, rapidamente é direcionado para a página desejada. Tudo foi planejado e elaborado de acordo com nosso wireframe.

> Apresente as principais interfaces da solução. Discuta como 
> foram elaboradas de forma a atender os requisitos funcionais, não
> funcionais e histórias de usuário abordados nas [Especificações do
> Projeto](#especificações-do-projeto).

## User Flow

Um arquivo foi adicionado na pasta com o nome Pdl_Converta_User_Flow.pdf com o fluxo de usúario feito pelo grupo.

> Fluxo de usuário (User Flow) é uma técnica que permite ao desenvolvedor
> mapear todo fluxo de telas do site ou app. Essa técnica funciona
> para alinhar os caminhos e as possíveis ações que o usuário pode
> fazer junto com os membros de sua equipe.
>
> **Links Úteis**:
> - [User Flow: O Quê É e Como Fazer?](https://medium.com/7bits/fluxo-de-usu%C3%A1rio-user-flow-o-que-%C3%A9-como-fazer-79d965872534)
> - [User Flow vs Site Maps](http://designr.com.br/sitemap-e-user-flow-quais-as-diferencas-e-quando-usar-cada-um/)
> - [Top 25 User Flow Tools & Templates for Smooth](https://www.mockplus.com/blog/post/user-flow-tools)
>
> **Exemplo**:
> 
> ![Exemplo de UserFlow](images/userflow.jpg)


## Wireframes

Nossas ilustrações dos wireframes estão disponíveis em um arquivo dessa pasta aqui: Wireframe-converta.

> Wireframes são protótipos das telas da aplicação usados em design de interface para sugerir a
> estrutura de um site web e seu relacionamentos entre suas
> páginas. Um wireframe web é uma ilustração semelhante ao
> layout de elementos fundamentais na interface.
> 
> **Links Úteis**:
> - [Ferramentas de Wireframes](https://rockcontent.com/blog/wireframes/)
> - [Figma](https://www.figma.com/)
> - [Adobe XD](https://www.adobe.com/br/products/xd.html#scroll)
> - [MarvelApp](https://marvelapp.com/developers/documentation/tutorials/)
> 
> **Exemplo**:
> 
> ![Exemplo de Wireframe](images/wireframe-example.png)


# Metodologia

Fizemos nosso controle de tarefas pelo Trello, em que as tarefas vinculadas a algum membro do grupo específico foram indicadas no quadro. As tarefas sem pessoas específicas foram divididas para que depois fosse tudo inserido em uma única pasta. 
Link do site de design thinking https://trello.com/b/8AygzjUA/tutorial-trello

> Nesta parte do documento, você deve apresentar a metodologia 
> adotada pelo grupo, descrevendo o processo de trabalho baseado nas metodologias ágeis, 
> a divisão de papéis e tarefas, as ferramentas empregadas e como foi realizada a
> gestão de configuração do projeto via GitHub.
>
> Coloque detalhes sobre o processo de Design Thinking e a implementação do Framework Scrum seguido
> pelo grupo. O grupo poderá fazer uso de ferramentas on-line para acompanhar
> o andamento do projeto, a execução das tarefas e o status de desenvolvimento
> da solução.
> 
> **Links Úteis**:
> - [Tutorial Trello](https://trello.com/b/8AygzjUA/tutorial-trello)
> - [Gestão ágil de projetos com o Trello](https://www.youtube.com/watch?v=1o9BOMAKBRE)
> - [Gerência de projetos - Trello com Scrum](https://www.youtube.com/watch?v=DHLA8X_ujwo)
> - [Tutorial Slack](https://slack.com/intl/en-br/)

## Divisão de Papéis

A equipe foi organizada assim:
Projeto: Conversor de Medidas
Scrum Master: Leonardo Vilela Cardoso
Equipe de Desenvolvimento:
Thales Cançado e Henrique (Desenvolvedor Front End)
Arthur e Marcos Filipe (Desenvolvedor Back End)
Luisa Machado e Luiza (Analista de Negócios)
Rodrigo Duarte (Desenvolvedor Front End)
Riquelme Oliveira(Designer)


> Apresente a divisão de papéis e tarefas entre os membros do grupo.
>
> **Links Úteis**:
> - [11 Passos Essenciais para Implantar Scrum no seu Projeto](https://mindmaster.com.br/scrum-11-passos/)
> - [Scrum em 9 minutos](https://www.youtube.com/watch?v=XfvQWnRgxG0)


## Ferramentas

| Ambiente  | Plataforma              |Link de Acesso |
|-----------|-------------------------|---------------|
|Processo de Design Thinkgin  | Trello |  https://trello.com/b/PSC1p3Gf/controle-de-tarefas | 
|Repositório de código | GitHub | https://github.com/XXXXXXX | 
|Hospedagem do site | Heroku |  https://XXXXXXX.herokuapp.com | 
|Protótipo Interativo | Figma |  | 

| Ambiente  | Plataforma              |Link de Acesso |
|-----------|-------------------------|---------------|
|Processo de Design Thinkgin  | Miro |  https://miro.com/XXXXXXX | 
|Repositório de código | GitHub | https://github.com/XXXXXXX | 
|Hospedagem do site | Heroku |  https://XXXXXXX.herokuapp.com | 
|Protótipo Interativo | MavelApp ou Figma | https://figma.com/XXXXXXX | 

>
> Liste as ferramentas empregadas no desenvolvimento do
> projeto, justificando a escolha delas, sempre que possível.
> 
> As ferramentas empregadas no projeto são:
> 
> - Editor de código.
> - Ferramentas de comunicação
> - Ferramentas de diagramação
> - Plataforma de hospedagem
> 
> O editor de código foi escolhido porque ele possui uma integração com o
> sistema de versão. As ferramentas de comunicação utilizadas possuem
> integração semelhante e por isso foram selecionadas. Por fim, para criar
> diagramas utilizamos essa ferramenta por melhor captar as
> necessidades da nossa solução.
> 
> **Links Úteis - Hospedagem**:
> - [Getting Started with Heroku](https://devcenter.heroku.com/start)
> - [Crie seu Site com o HostGator](https://www.hostgator.com.br/como-publicar-seu-site)
> - [GoDady](https://br.godaddy.com/how-to)
> - [GitHub Pages](https://pages.github.com/)

## Controle de Versão

......  COLOQUE AQUI O SEU TEXTO ......

> Discuta como a configuração do projeto foi feita na ferramenta de
> versionamento escolhida. Exponha como a gerência de tags, merges,
> commits e branchs é realizada. Discuta como a gerência de issues foi
> realizada.
> A ferramenta de controle de versão adotada no projeto foi o
> [Git](https://git-scm.com/), sendo que o [Github](https://github.com)
> foi utilizado para hospedagem do repositório `upstream`.
> 
> O projeto segue a seguinte convenção para o nome de branchs:
> 
> - `master`: versão estável já testada do software
> - `unstable`: versão já testada do software, porém instável
> - `testing`: versão em testes do software
> - `dev`: versão de desenvolvimento do software
> 
> Quanto à gerência de issues, o projeto adota a seguinte convenção para
> etiquetas:
> 
> - `bugfix`: uma funcionalidade encontra-se com problemas
> - `enhancement`: uma funcionalidade precisa ser melhorada
> - `feature`: uma nova funcionalidade precisa ser introduzida
>
> **Links Úteis**:
> - [Tutorial GitHub](https://guides.github.com/activities/hello-world/)
> - [Git e Github](https://www.youtube.com/playlist?list=PLHz_AreHm4dm7ZULPAmadvNhH6vk9oNZA)
> - [5 Git Workflows & Branching Strategy to deliver better code](https://zepel.io/blog/5-git-workflows-to-improve-development/)
>
> **Exemplo - GitHub Feature Branch Workflow**:
>
> ![Exemplo de Wireframe](images/Github-Workflow.png)

# **############## SPRINT 1 ACABA AQUI #############**


# Projeto da Solução

......  COLOQUE AQUI O SEU TEXTO ......

## Tecnologias Utilizadas

......  COLOQUE AQUI O SEU TEXTO ......

> Descreva aqui qual(is) tecnologias você vai usar para resolver o seu
> problema, ou seja, implementar a sua solução. Liste todas as
> tecnologias envolvidas, linguagens a serem utilizadas, serviços web,
> frameworks, bibliotecas, IDEs de desenvolvimento, e ferramentas.
> Apresente também uma figura explicando como as tecnologias estão
> relacionadas ou como uma interação do usuário com o sistema vai ser
> conduzida, por onde ela passa até retornar uma resposta ao usuário.
> 
> Inclua os diagramas de User Flow, esboços criados pelo grupo
> (stoyboards), além dos protótipos de telas (wireframes). Descreva cada
> item textualmente comentando e complementando o que está apresentado
> nas imagens.

## Arquitetura da solução

......  COLOQUE AQUI O SEU TEXTO E O DIAGRAMA DE ARQUITETURA .......

> Inclua um diagrama da solução e descreva os módulos e as tecnologias
> que fazem parte da solução. Discorra sobre o diagrama.
> 
> **Exemplo do diagrama de Arquitetura**:
> 
> ![Exemplo de Arquitetura](images/arquitetura-exemplo.png)


# Avaliação da Aplicação

......  COLOQUE AQUI O SEU TEXTO ......

> Apresente os cenários de testes utilizados na realização dos testes da
> sua aplicação. Escolha cenários de testes que demonstrem os requisitos
> sendo satisfeitos.

## Plano de Testes

......  COLOQUE AQUI O SEU TEXTO ......

> Enumere quais cenários de testes foram selecionados para teste. Neste
> tópico o grupo deve detalhar quais funcionalidades avaliadas, o grupo
> de usuários que foi escolhido para participar do teste e as
> ferramentas utilizadas.
> 
> **Links Úteis**:
> - [IBM - Criação e Geração de Planos de Teste](https://www.ibm.com/developerworks/br/local/rational/criacao_geracao_planos_testes_software/index.html)
> - [Práticas e Técnicas de Testes Ágeis](http://assiste.serpro.gov.br/serproagil/Apresenta/slides.pdf)
> -  [Teste de Software: Conceitos e tipos de testes](https://blog.onedaytesting.com.br/teste-de-software/)

## Ferramentas de Testes (Opcional)

......  COLOQUE AQUI O SEU TEXTO ......

> Comente sobre as ferramentas de testes utilizadas.
> 
> **Links Úteis**:
> - [Ferramentas de Test para Java Script](https://geekflare.com/javascript-unit-testing/)
> - [UX Tools](https://uxdesign.cc/ux-user-research-and-user-testing-tools-2d339d379dc7)

## Registros de Testes

......  COLOQUE AQUI O SEU TEXTO ......

> Discorra sobre os resultados do teste. Ressaltando pontos fortes e
> fracos identificados na solução. Comente como o grupo pretende atacar
> esses pontos nas próximas iterações. Apresente as falhas detectadas e
> as melhorias geradas a partir dos resultados obtidos nos testes.


# Referências

https://mestresdaweb.com.br/fabrica-de-software/requisitos-funcionais-e-nao-funcionais-o-que-sao/#:~:text=Os%20requisitos%20n%C3%A3o%20funcionais%20s%C3%A3o,funcionais%20descrevem%20como%20ser%C3%A3o%20feitos  Acesso em: 09 abr. 2022.

https://www.atlassian.com/br/agile/project-management/user-stories  Acesso em: 09 abr. 2022.

VIDDIA. Como construir um mapa de empatia? 2018. Disponível em: https://viddia.com.br/como-construir-mapa-de-empatia/. Acesso em: 07 abr. 2022.

Guia do Scrum™ - Um guia definitivo para o Scrum: As regras do jogo - Desenvolvido e mantido por Ken Schwaber e Jeff Sutherland

Timezone-picker - Mapa interativo. Disponível em: dosx/timezone-picker: A Google Maps (or OpenLayers) + Olson Time Zones mashup to do a timezone picker (github.com) . Acesso em: 09 abr. 2022.


> Inclua todas as referências (livros, artigos, sites, etc) utilizados
> no desenvolvimento do trabalho.
> 
> **Links Úteis**:
> - [Formato ABNT](https://www.normastecnicas.com/abnt/trabalhos-academicos/referencias/)
> - [Referências Bibliográficas da ABNT](https://comunidade.rockcontent.com/referencia-bibliografica-abnt/)
