# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

A definição do problema e os pontos mais relevantes a serem tratados neste projeto foram consolidados com base nas experiências pessoais, relacionadas ao tema, compartilhada por alguns membros do grupo. A partir desses relatos, inferimos outros possíveis problemas dos usuários. Os detalhes levantados nesse processo foram organizados em personas e histórias de usuários. 

## Personas
As personas levantadas durante o processo de entendimento do problema são apresentadas nas tabelas que se seguem:

Persona | 1
---|---
<img src="img/personas/persona1.PNG" width="150" height="150" />| **Camila Silva**  
**Idade:** 19 **Ocupação:** Estudante **Hobbies:** Literatura|**Aplicativos:** Instagram, Skoob, Apps bancários, Netflix, WhatsApp, Telegram  
**Motivações:** Gosta de ler livros. Gostaria de aumentar seu círculo de amizades. Quer melhorar sua habilidade de comunicação.|**Frustrações:** Sofre com a dificuldade de estabelecer interações com pessoas. É muito tímida e se sente tensa durante diálogos por não saber o que dizer.
**Persona** | **2** 
<img src="img/personas/persona2.PNG" width="150" height="150" />| **Carlos Santos** 
**Idade:** 71 **Ocupação:** Aposentado **Hobbies:** Literatura|**Aplicativos:** Facebook, Aplicativos de bancos, Whatsapp
**Motivações:** Gosta de literatura. Gosta de sair para encontrar pessoas e conversar.|**Frustrações:** Se sente solitário e triste devido ao isolamento social provocado pela pandemia de Covid-19. 
**Persona** | **3**
<img src="img/personas/persona3.PNG" width="150" height="150" />| **Maria Ferreira** 
**Idade:** 39 **Ocupação:** Escritora iniciante **Hobbies:** Literatura, Escrita criativa |**Aplicativos:** Facebook, Instagram, Whatsapp, Aplicativos de bancos 
**Motivações:** Gosta de ler romances. Quer escrever seu próprio livro.|**Frustrações:** Não consegue encontrar alguém para compartilhar os capítulos já escritos de seu romance e obter um feedback. Possui muitas tarefas para realizar diariamente. 
**Persona** | **4**
<img src="img/personas/persona4.PNG" width="150" height="150" />| **Ana Oliveira** 
**Idade:** 57 **Ocupação:** Aposentada **Hobbies:** Literatura |**Aplicativos:** Whatsapp, Youtube 
**Motivações:** Passa a maior parte do tempo escutando audiolivros em casa. |**Frustrações:** Sente dificuldade de interagir com a tecnologia. Possui baixa visão e precisa do auxílio de ferramentas leitoras de tela. 
**Persona** | **5**
<img src="img/personas/persona5.PNG" width="150" height="150" />| **Miguel Lima** 
**Idade:** 26 **Ocupação:** Afastado do emprego **Hobbies:** Literatura |**Aplicativos:** Instagram, Skoob, Apps bancários, Netflix, WhatsApp, Telegram  
**Motivações:** Gostaria de voltar a frequentar clubes de literatura. Quer encontrar novas recomendações de livros. |**Frustrações:** Devido a um acidente, desenvolveu dificuldade de mobilidade. Não sai de casa tanto quanto gostaria.



## Histórias de Usuários

Com base na análise das personas identificadas para o projeto, foram formuladas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Camila Silva | Quero melhorar minha forma de comunicação | Para que eu possa me sentir mais confortável ao conversar e assim, ter mais qualidade de vida |
|Camila Silva | Quero encontrar pessoas com interesses em comum | Para que isso facilite nossa interação e eu encontre novos amigos |
|Carlos Santos | Quero encontrar companhia | Para que eu me sinta menos solitário e possa ter boas conversas de forma online ou marcar encontros pessoalmente |
|Maria Ferreira | Quero ler comentários sobre meu livro, mesmo tendo uma rotina atarefada | Para que eu possa visualizar os feedbacks recebidos durante vários contextos da minha rotina, sem deixar de reaizar alguma tarefa |
|Ana Oliveira |Quero encontrar novos livros |Para que eu descubra mais opções de entretenimento |
|Ana Oliveira | Quero acessar mais aplicativos, apesar de ter dificuldade durante o uso | Para que eu me beneficie das funcionalidades oferecidas |
|Ana Oliveira | Quero encontrar sites bem adaptados para leitores de tela | Para que minha baixa visão não atrapalhe a experiência de uso.|
|Miguel Lima | Quero realizar atividades que gosto de forma remota| Para que minha dificuldade de mobilidade não proiba minha conexão a assuntos que me fazem bem. |


## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| A aplicação  deve apresentar, na página principal, a funcionalidade de cadastro de usuários para que esses consigam criar e gerenciar seu perfil. | ALTA | 
|RF-002| A aplicação deve ter um chat para conversação para os usuários interagirem entre si. | MÉDIA |
|RF-003| A aplicação  deve oferecer uma funcionalidade de filtro/pesquisa para permitir ao usuário localizar livros. | ALTA |
|RF-004| A aplicação  deve possuir a opção de não mostrar todos os dados do usuário. | ALTA |
|RF-005| A aplicação  deve possuir opção de fazer login, sendo o login endereço de e-mail. | ALTA|
|RF-006| A página web  deve possuir as opções de inserir listas de livros e de salvá-las. | ALTA |
|RF-007| A aplicação  deve permitir mostrar uma parte do perfil de outros usuários para facilitar o encontro de listas de livros. | BAIXA |
|RF-008| A aplicação  deverá permitir buscar livros previamente cadastrados na base de dados. | BAIXA |
|RF-009| A aplicação  deve permitir a função _match_ quando um usuário se identificou com outro usuário. | ALTA |
|RF-010| A aplicação  deve permitir que usuários façam comentários sobre os livros.	 | MÉDIA |
|RF-011| A aplicação  deve listar e reunir os livros com mais _matches_. | BAIXA |
|RF-012| A aplicação  deve permitir que o login seja efetuado com a conta Google e com o Facebook. |ALTA|


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| A aplicação  deve ser publicado em um ambiente acessível publicamente na Internet (GitHub Pages, Heroku). | ALTA | 
|RNF-002| A aplicação  deverá ser responsiva. | ALTA | 
|RNF-003| A aplicação  deve ser construída considerando a forma com que os leitores irão ler. | MÉDIA |
|RNF-004| A aplicação  deve ser compatível com os principais navegadores do mercado (Google Chrome, Firefox, Microsoft Edge). | ALTA |
|RNF-005| A aplicação  deve possuir leitores de tela, para que pessoas com deficiências visuais possam utilizar a plataforma. | MÉDIA |
|RNF-006| A aplicação  deve possuir uma tela simples e intuitiva, com base nos pressupostos do Design de Interação, para que pessoas com dificuldades em tecnologias possam utilizá-la.  | ALTA |
|RNF-007| A aplicação  deve permitir salvar as informações dos usuários respeitando a LGPD.  | MÉDIA |
|RFN-008| A aplicação  deve possuir um sistema adaptado para pessoas com deficiências visuais. | ALTA|

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|RE-01| O projeto deverá ser entregue no final do semestre letivo, não podendo extrapolar a data de 26/06/2022.   |
|RE-02| O aplicativo deve utilizar conhecimentos de SQL e Modelagem de Dados, Engenharia de Requisitos de Software, Programação Modular, Algoritmos e Estruturas de Dados, Desenvolvimento Web Back-End e Front-End e Fundamentos de Redes de Computadores.          |
|RE-03| A equipe não pode subcontratar o desenvolvimento do trabalho.        |


## Diagrama de Casos de Uso

O diagrama de casos de uso é o próximo passo após a elicitação de requisitos, que utiliza um modelo gráfico e uma tabela com as descrições sucintas dos casos de uso e dos atores. Ele contempla a fronteira do sistema e o detalhamento dos requisitos funcionais com a indicação dos atores, casos de uso e seus relacionamentos. 

<img src="https://user-images.githubusercontent.com/81396458/157950178-ccef1fec-fc98-44a4-a541-b8887d015d38.png" width="70%"/>
