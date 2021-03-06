# Desafio01-PB-REC@NodeJs

##### Primeiro desafio do Programa de Bolsas REC@nodejs da compass.uol!

### Perguntas: 
###### [Clique nas perguntas para abrir as respostas]

<details><summary><b>1. Para que serve o método Scrum?<b></summary>
<div align="justify">
&emsp;Scrum serve para estabelecer um método ágil de desenvolvimento no projeto, auxiliando na criação e entrega do produto para o cliente de forma cíclica, apresentando partes do projeto no final de uma sprint.
</div>
</details>

<details><summary><b>2. Como funciona o método Scrum?<b></summary>
<div align="justify">
        &emsp;O Scrum trabalha de forma cíclica, que são chamadas de sprints, passando por 4 etapas: Sprint Planning, Desenvolvimento, Sprint Review e Sprint Retrospective. Os envolvidos são stakeholders, Product Owner, Scrum Master e Desenvolvedores. <br>
        &emsp;O Product Owner fica responsável pela parte de negócios, tendo maior contato com o cliente e representando ele durante algumas etapas.<br>
        &emsp;A função do Scrum Master é oferecer suporte ao trabalhar com essa metodologia e auxiliar nas dificuldades dos desenvolvedores.<br>
        &emsp;Os desenvolvedores são todos que irão fazer parte deste projeto.<br>
        &emsp;O PO fica responsável por conversar com o cliente e elaborar a Product Backlog, uma lista com as funcionalidades do projeto ordenadas por prioridade (maior valor agregado para o produto), onde será apresentada no início da Sprint na etapa da Sprint Planning, essa lista passa por um processo de refinação pelo PO antes de ir para esta reunião, transformando as funcionalidades em user stories.<br>
        &emsp;Durante à reunião, a equipe é reunida e juntos definem a Sprint Backlog, uma lista com as funcionalidades a serem desenvolvidas durante a etapa de desenvolvimento. Nessa lista é transformada as users stories em tarefas, as quais serão atribuídas para os desenvolvedores.<br>
        &emsp;Na etapa de desenvolvimento é realizado reuniões diárias (daily meeting) para acompanhar o progresso de cada dev e auxiliar caso haja problemas ou impedimentos.<br>
        &emsp;Após a etapa de desenvolvimento, ocorre a Sprint Review, uma reunião com todos os envolvidos do projeto (stakeholders e scrum team) para apresentação das funcionalidades que foram adicionadas ao projeto durante o sprint, nessa etapa temos o feedback do cliente, possíveis sugestões de mudanças ou novas ideias.<br>
        &emsp;Ao passar pelo Review temos a Sprint Retrospective onde somente a equipe se junta para discutir como foi aquela sprint, com o objetivo de identificar dificuldades e eloborar novas estratégias para o próximo sprint e assim se encerra este.<br>
        &emsp;O Scrum ocorre de forma cíclica então após a finalização da Retrospective no próximo dia útil é feito a Planning decidindo quais serão as outras tarefas a serem feitas durante essa nova sprint e assim se continua o ciclo até o fim do projeto.</div>
</details>

<details><summary><b>3. O que é Git?<b></summary>
    <div align="justify">
        &emsp;Git é um sistema para controle de versionamento de códigos, sendo recomendado utilizar para desenvolvimento de softwares por sua grande perspicácia em salvar pontos do desenvolvimento, podendo recuperar dados de versões anteriores se necessário.
    </div>
</details>

<details><summary><b>4. O que é um scrum Product Owner?<b></summary>
    <div align="justify">
        &emsp;Scrum Product Owner é responsável pela visão de negócio dentro do projeto, tem como suas funções extrair do cliente informações para a construção da Product Backlist e apresenta-las aos desenvolvedores de forma mais refinada. É a principal comunicação com o cliente, sempre ovindo novas ideias e alterações.<br>
        &emsp;É desejável que o PO mantenha a Produckt Backlist sempre atualizada e que participe de todas as etapas da sprint.
    </div>
</details>

<details><summary><b>5. Qual o comando para criação de um novo repositório no Git?<b></summary>
    <div align="justify">
        &emsp;git init
    </div>
</details>

<details><summary><b>6. O que é o HTTP?<b></summary>
    <div align="justify">
        &emsp;HTTP é um protocolo para estabelecer regras de comunicação do cliente com o servidor através de métodos de conexão. (GET, POST, PUT, PATCH, DELETE)
    </div>
</details>

<details><summary><b>7. Como funciona o HTTP?<b></summary>
    <div align="justify">
        &emsp;O HTTP trabalha com requisição e resposta, declarando como o cliente e servidor devem enviar e receber dados. Como exemplo, no HTTP temos diversos métodos, e se o servidor não estiver preparado para trafegar dados em uma URL com o método especificado terá uma resposta de erro como o 404 NOT FOUND por não encontrar a página.
    </div>
</details>

<details><summary><b>8. Com o Git Você pode propor mudanças (adicioná-las ao Index) usando um comando. Qual é esse comando?<b></summary>
    <div align="justify">
        &emsp;git add index.html
    </div>
</details>

<details><summary><b>9. O que é a Branch master e para que serve?<b></summary>
    <div align="justify">
        &emsp;A master serve como a branch principal do nosso projeto, podemos criar outras branchs através dela para desenvolvimento, mas sempre deixamos o código "funcional" nela.
    </div>
</details>

<details><summary><b>10. Quais são os comandos usados para atualizar um repositório local e fazer merge de um outro branch ao seu branch ativo?<b></summary>
    <div align="justify">
        &emsp;Atulizar repositório local:<br>
        &emsp;&emsp;- git pull<br>
        &emsp;Fazer merge:<br>
        &emsp;&emsp;- git merge branchName
    </div>
</details>

<details><summary><b>11. Qual a diferença entre git e github?<b></summary>
    <div align="justify">
        &emsp;O git é um sistema de versionamento de código, enquanto o github é uma plataforma pronta para receber, armazenar e compartilhar no formato deste sistema.
    </div>
</details>

<details><summary><b>12. Quais os dois verbos http que podemos utiizar para realizar um update? Explique a diferença entre eles.<b></summary>
    <div align="justify">
        &emsp;PUT: Utilizado para atualizar uma entidade por completo.<br>
        &emsp;PATCH: Utilizado para atualizar parte desta entidade.
    </div>
</details>

<details><summary><b>13. Qual o status code que pode ser usado na criação de um novo usuário?<b></summary>
    <div align="justify">
        &emsp;201: Criado
    </div>
</details>

<details><summary><b>14. Quais são os três status code que modem ser utilizados para realizar o delete?<b></summary>
    <div align="justify">
        &emsp;200: OK<br>
        &emsp;202: Aceito<br>
        &emsp;204: Solicitação bem sucedida
    </div>
</details>

<details><summary><b>15. Exemplifique para que serve os metódos http 1xx, 2xx, 3xx, 4xx e 5xx. De uma forma macro (geral)!<b></summary>
    <div align="justify">
        &emsp;1XX: Resposta informativa<br>
        &emsp;2XX: Resposta de sucesso<br>
        &emsp;3XX: Resposta de redirecionamento<br>
        &emsp;4XX: Resposta de erro do cliente<br>
        &emsp;5XX: Resposta de erro do servidor
    </div>
</details>

<details><summary><b>16. Conta pra gente como foi sua experiência na Sprint#01 do programa de bolsa @node.js_mar22 e quais suas expectativas a partir de agora:<b></summary>
    <div align="justify">
        &emsp;Estou gostando muito por estar participando desta experiência e além de poder melhorar meus conhecimentos, estou aprendendo na prática.<br>
        &emsp;Muito bom conhecer pessoas novas, conversei com outros bolsistas e sinto que todos estamos anciosos, mas com grandes expectativas para alavancar nosso conhecimento e aos poucos vou me sentindo mais a vontade.<br>
        &emsp;Para o próximo sprint sinto que com essa equipe irei aprender e me desenvolver bastante!
    </div>
</details>