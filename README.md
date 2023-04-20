## _**PancreAmigos**_


# Objetivo Principal:

### Auxiliar nas decisões tomadas por pessoas portadoras da diabetes tipo 1 em relação ao seu tratamento. Com isso, busca-se auxiliar na qualidade e expectativa de vida dessas pessoas, auxiliando-as a tomar as decisões corretas.



## Equipe de Desenvolvimento:

Dev Master - Marcos Paulo Amorim - @mpauloribeiroa<br>
Dev CI Tester - Liander Medeiros - @liander-medeiros<br>
Dev Back - Felipe Guimaraes - @felipegf1<br>
Dev Back - Igor Alves - @igorabreueng<br>
Dev Front - Pedro Miguel dos Santos - @pedromadbr<br>

<br>

### **Sumário**

- [_**PancreAmigos**_](#PancreAmigos)
  - [**Sumário**](#sumário)
- [VISÃO GERAL DO PRODUTO](#visão-geral-do-produto)
  - [1.1 Declaração de Posição do Produto](#11-declaração-de-posição-do-produto)
  - [1.2. Objetivos do Produto](#12-objetivos-do-produto)
  - [1.3. Tecnologias a Serem Utilizadas](#13-tecnologias-a-serem-utilizadas)
- [VISÃO GERAL DO PROJETO](#visão-geral-do-projeto)
    - [2.1 Organização do Projeto](#21-organização-do-projeto)
- [REFERÊNCIAS BIBLIOGRÁFICAS](#referências-bibliográficas)

<br>

## VISÃO GERAL DO PRODUTO

### 1.1 Declaração de Posição do Produto

|                  |                                                                                                      |
| :--------------- | --------------------------------------------------------------------------------------------------- |
| Para             | Portadores de Diabete Tipo 1                                                   |
| Quem             | precisa de auxílio no tratamento diário                                        |
| O PancreAmigo    | é um auxiliador                                                                |
| Que              | ajuda a tomar decisões diárias compilando informações necessárias e automatizando cálculos           |
| Ao contrário de  | de a própria pessoa tomar as decisões sem auxílio nenhum, e fazer os cálculos de forma potencialmente imprecisa |
| Nosso produto    | se diferencia por apresentar todas as funções necessárias para auxiliar com praticidade uma pessoa com diabetes. |

<br>

### 1.2. Objetivos do Produto

O objetivo principal do produto é auxiliar nas decisões tomadas por pessoas portadoras da diabetes tipo 1 em relação ao seu tratamento. Com isso, busca-se auxiliar na qualidade e expectativa de vida dessas pessoas, auxiliando-as a tomar as decisões corretas. <br>

Dentro das funcionalidades, o objetivo de ajudar na tomada de decisões se divide em algumas frentes. O primeiro objetivo é atuar como um diário, recebendo os registros dos valores das medições de glicemia do usuário. Esse registro é fundamental para a análise do tratamento, especialmente considerando tomadas de decisões mais amplas, envolvendo a rotina do usuário.<br>

Além disso, outro objetivo é poder calcular as dosagens de insulina necessárias para cada aplicação, com base na glicemia informada e na refeição do usuário. As informações para fazer esse cálculo ficam dispersas, o que atrapalha na praticidade e precisão desse cálculo. Portanto, compilar essas informações e fazer esse cálculo de forma precisa levará a um grande aumento na qualidade de vida do usuário. <br>

Além disso, outro objetivo é exibir informações relevantes para o tratamento, inclusive por meio de notificações. Entendemos que o usuário tem que administrar um grande número de informações, além de ter que acompanhar as decisões que tomou ao longo do dia. Reunir essas informações e notificar o usuário sobre as mais relevantes pode ajudar a um acompanhamento melhor do tratamento.<br>


<br>

### 1.3. Tecnologias a Serem Utilizadas

O Flutter foi a tecnologia a ser escolhida por ter uma configuração simples e com uma boa documentação, auxiliando no desenvolvimento do nosso produto dessa forma será utilizada no frontend e backend.<br>

Já para o banco de dados, a tecnologia de fácil aprendizado para a equipe e com boa integração com o Flutter a ser escolhida foi PostgreSQL.<br>


<br>


## VISÃO GERAL DO PROJETO

<br>

### 2.1 Organização do Projeto

| Papel                        | Atribuições                                                                                                                                          | Responsável              | Participantes                           |
| :--------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------ | --------------------------------------- |
| Desenvolvedor Front-end      | Desenvolver o produto na parte visual, manipulando os dados, para mostrar ao cliente de forma legível, e enviar ao backend de forma bem estruturada. | Pedro Miguel dos Santos              | Pedro Miguel dos Santos e Marcos Paulo Amorim              |
| CI Tester | Desenvolver banco de dados, tabelas, relações entre as mesmas, e demais necessidades de banco.                                                       | Liander Medeiros         | Liander Medeiros                        |
| Desenvolvedor Back-end       | Desenvolver conversação com o banco de dados, manusear os dados, para serem inseridos no banco, e apresentados no front-end.                         | Igor Alves             | Igor Alves e Felipe Guimaraes |
| Cliente                      | Atualizar o escopo do produto, organizar o escopo das sprints, validar as entregas | Julia Guimarães e Professor |     

<br>

### 2.2 Planejamento das Fases e/ou Iterações do Projeto

Ainda não definido

<br>

### 2.3 Matriz de Comunicação

| Descrição                                                               | Envolvidos         | Periodicidade | Produtos Gerados                                                           |
| :---------------------------------------------------------------------- | ------------------ | ------------- | -------------------------------------------------------------------------- |
| -Acompanhamento das Atividades em Andamento;                            | -Equipe do projeto | -2 dias      | -Ata da Reunião e Relatório de Situação do Projeto                                                                    |
| -Alinhamento de expectativas e requisitos para próxima sprint | -Equipe do Projeto | - 14 dias    | - Lista de requisitos candidatos a estar no backlog da proxima sprint |
| -Sprints                                                 | -Equipe do projeto        | - 14 dias     | -Incremento de valor                            | 
Comunicação de Situação do Projeto | - Equipe e Professor | Pontos de controle | - Ata de reunião e - Relatório de Situação do Projeto | 

<br>

### 2.4 Gerenciamento de Riscos

Risco leve: Dificuldade de Comunicação<br>
Risco Moderado: falta de Familiaridade com a Tecnologia, Gerenciamento de Horário<br>
Risco Grave: diminuição da Equipe<br>


<br>

### 2.5 Critérios de Replanejamento

Redução no Número de Membros da Equipe
Escopo maior que o esperado, baseado no nosso conhecimento da tecnologia


## PROCESSO DE DESENVOLVIMENTO DE SOFTWARE

<br>

### 3.1 Elaboração de Requisitos

| Atividade                              | Método                                                                                                                                                | Ferramenta                                     | Entrega                                                  |
| :------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------- | -------------------------------------------------------- |
| Elicitação de requisitos               | Necessidade do Cliente e Brainstorming                                                                                                                                         | Trello e Miro                                         | Backlog do produto                                       |
| Análise dos requisitos                 | Diferenciação dos RF e RNF                                                                                                                            | Google meet                                   | Lista de requisitos                                        |
| Documentação de requisitos             | Organizar os requisitos em cronologia estratégica                                                                  | Miro                                           | Backlog do produto |

<br>

### 3.2 Sprint Review e Sprint Retro

| Atividade                         | Método         | Ferramenta | Entrega                      |
| :-------------------------------- | -------------- | ---------- | ---------------------------- |
| Validação com o Cliente    | Apresentação | Google Meet      | Validação baseada nos requisitos |
| Verificação       | Reunião | Google Meet    | Verificar o resultado do planejamento     |

<br>

## LIÇÕES APRENDIDAS

### Unidade 1

O principal aprendizado foi o conhecimento das ferramentas de gerenciamento de projeto, usando as metodologias como o Scrum e o XP.<br>

Aos poucos também começamos a entender o nível de conhecimento de cada membro do time dessa forma foi possível delimitar práticas a serem adotadas em nosso projeto.<br>

<br>

## REFERÊNCIAS BIBLIOGRÁFICAS

- [Materiais Disponibilizados no Moodle](https://aprender3.unb.br/login/index.php)
- [SAUDE, Ministério da. 26/6 – Dia Nacional do Diabetes. Biblioteca Virtual em Saúde MINISTÉRIO DA SAÚDE, 2023.](https://bvsms.saude.gov.br/26-6-dia-nacional-do-diabetes-4/#:~:text=Em%202020%2C%20calcula%2Dse%20que,2025%2C%20era%20de%20438%20milh%C3%B5es)

- [SOBRENOME, Nome. Título da matéria. Nome do site, ano. Disponível em: URL DIABETES, Associação Nacional de Atenção ao. Expectativa de Vida do Diabetes. ANAD, 2023.](https://www.anad.org.br/expectativa-da-vida-no-diabetes/)

- [Documentação do Postgres](https://www.postgresql.org/)

<br>

# Apresentação  da Unidade 1

<iframe width="760" height="515" src="" title="Aprensentação de Entrega da Unidade 1, PancreAmigos" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
