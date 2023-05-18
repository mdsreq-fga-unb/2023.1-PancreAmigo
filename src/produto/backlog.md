# Backlog do Produto

Estão dispostos os requisitos a serem trabalhados pela equipe, separados por temas, épicos e histórias de usuário. Eles foram organizados de acordo com a prioridade do cliente e viabilidade entre eles, já que vários requisitos dependem de outros para existir.

# Temas

T1 - Dados Pessoais
T2 - Dados Médicos
T3 - Regras de Negócio

# Épicos

E1 - Cadastramento
E2 - Alimentação
E3 - Dados sobre Insulina
E4 - Dados sobre Glicemia
E5 - Indicações
E6 - Notificações
E7 - Gráficos


# Histórias de Usuário

VN: Valor de negócio
Ve: Viabilidade
C: Complexidade

A pontuação do valor de negócio, viabilidade e complexidade foram definidos em uma escala de 1 a 5, e a pontuação total foi obtida somando o valor de negócio, a viabilidade e a complexidade.


| Tema | Épico | US | História de Usuário | VN | Ve | C | Total |
| :----: | :-----: | :--: | ------------------- | :--: | :--: | :-: | :-----: |
| T1 | E1 | US1 | Eu, como usuário, cadastro meus dados para que as minhas informações sejam salvas corretamente | 1 | 3 | 1 | 5 |
| | | US2 | Eu, como usuário, vejo um perfil com todos meus dados cadastrais | 2 | 3 | 1 | 6 |
| | | US3 | Eu, como usuário, edito os meus dados de cadastro a fim de atualizar informações caso necessário | 2 | 3 | 2 | 7 |
| | E2 | US4 | Eu, como usuário, registro minha alimentação  para controlar a quantidade de carboidrato, proteína e gordura | 3 | 2 | 2 | 7 |
| | | US5 | Eu, como usuário, registro o tempo exato desde a última refeição para verificar o tempo para comer novamente | 2 | 3 | 2 | 7 |
| T2 | E3 | US6 | Eu, como usuário, registro a minha prescrição para que o aplicativo possa fazer os cálculos de forma correta | 3 | 3 | 1 | 7 |
| | | US7 | Eu, como usuário, registro quando fizer uma aplicação de insulina para manter um controle das minhas doses aplicadas | 2 | 2 | 1 | 5 |
| | | US8 | Eu, como usuário, registro as aplicações por quantidade de unidades e por tipo de insulina para manter uma lista detalhada dos recursos utilizados | 2 | 3 | 1 | 6 | 
| | | US9 | Eu, como usuário, vejo quando fiz a última aplicação para não ter excesso de insulina em atividade no meu corpo | 2 | 2 | 2 | 6 |
| | E4 | US10 | Eu, como usuário, vejo o valor da última medição de glicemia | 3 | 3 | 1 | 7 |
| | | US11 | Eu, como usuário, registro os meus valores de glicemia a cada aferição para não perder o acompanhamento da minha rotina | 3 | 3 | 1 | 7 |
| T3 | E5 | US12 | Eu, como usuário, calculo a quantidade de insulina a ser aplicada em caso de hiperglicemia (quando o valor da glicemia está acima do ideal) | 3 | 3 | 2 | 8 |
| | | US13 | Eu, como usuário, recebo a quantidade de insulina a ser aplicada para corrigir uma refeição | 3 | 2 | 2 | 7 |
| | | US14 | Eu, como usuário, vejo uma estimativa do valor da minha hemoglobina glicada | 1 | 2 | 3 | 6 | 
| | E6 | US15 | Eu, como usuário, recebo a cada espaço de tempo (hora,dia) a aplicação de insulina basal (que precisa ser aplicada todo dia) | 4 | 2 | 2 | 8 |
| | | US16 | Eu, como usuário, edito a configuração das notificações para receber cada uma de acordo com o tempo desejado | 2 | 3 | 2 | 7 |
| | | US17 | Eu, como usuário, recebo uma notificação a cada espaço de tempo(hora,dia) sobre alimentação para que registre o que ingeri | 4 | 2 | 2 | 8 |
| | E7 | US18 | Eu, como usuário, listo todos os meus registros para visualizar minha rotina alimentícia e medicinal | 2 | 2 | 2 | 6 |
| | | US19 | Eu, como usuário, vejo as informações do meu registro em detalhes a fim de consultar aquilo que preenchi anteriormente | 2 | 1 | 2 | 5 |
| | | US20 | Eu, como usuário, vejo um gráfico dos meus registros a fim de acompanhar minha evolução no tratamento diabético | 3 | 1 | 1 | 5 |


# Requisitos não-funcionais

RNF001 - Implementação: O back-end e o front-end do produto deverá ser feito utilizando a tecnologia Flutter  
RNF002 - Suportabilidade: O produto estará disponível para smartphone android a partir da versão  5.0  
RNF003 - Confiabilidade: O produto deverá guardar os dados cadastrados do usuário respeitando a Lei nº 13.709/2018, conhecida como Lei Geral de Proteção de Dados (LGPD)  
RNF004 - Usabilidade: O produto deverá ter uma interface limpa, orientando de forma didática a usabilidade do produto. Além disso, por pedido da cliente, a interface deve ser azul e laranja.  


# Mínimo Produto Viável

MVP1

O objetivo desse MVP é fornecer um produto mínimo para que o usuário consiga registrar e manipular suas informações.


| Requisito | Descrição                                                                                                                                          |
|-----------|----------------------------------------------------------------------------------------------------------------------------------------------------|
| US1       | Eu, como usuário, cadastro meus dados para que as minhas informações sejam salvas corretamente                                                     |
| US2       | Eu, como usuário, vejo um perfil com todos meus dados cadastrais                                                                                   |
| US3       | Eu, como usuário, edito os meus dados de cadastro a fim de atualizar informações caso necessário                                                   |
| US4       | Eu, como usuário, registro minha alimentação  para controlar a quantidade de carboidrato, proteína e gordura                                       |
| US5       | Eu, como usuário, registro o tempo exato desde a última refeição para verificar o tempo para comer novamente                                       |
| US6       | Eu, como usuário, registro a minha prescrição para que o aplicativo possa fazer os cálculos de forma correta                                       |
| US7       | Eu, como usuário, registro quando fizer uma aplicação de insulina para manter um controle das minhas doses                                         |
| US8       | Eu, como usuário, registro as aplicações por quantidade de unidades e por tipo de insulina para manter uma lista detalhada dos recursos utilizados |
| US9       | Eu, como usuário, vejo quando fiz a última aplicação para não ter excesso de insulina em atividade no meu corpo                                    |
| US10      | Eu, como usuário, vejo o valor da última medição de glicemia                                                                                       |
| US11      | Eu, como usuário, registro os meus valores de glicemia a cada aferição para não perder o acompanhamento da minha rotina                            |


MVP2

O objetivo do MVP é conseguir ter acesso aos registros das informações inseridas, para habilitar o uso com o intuito de monitoramento a longo prazo. Além disso, esse MVP também traz a adição da manipulação de dados de forma direta, sem que o usuário precise inserir tudo manualmente.


| Requisito | Descrição                                                                                                                                                                                |
|-----------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| US 12     | Eu, como usuário, calculo a quantidade de insulina a ser aplicada em caso de hiperglicemia (quando o valor da glicemia está acima do ideal) para que não ocorra erros na minha medicação |
| US 13     | Eu, como usuário, recebo a quantidade de insulina a ser aplicada para corrigir uma refeição mal feita                                                                                    |
| US 14     | Eu, como usuário, vejo uma estimativa do valor da minha hemoglobina glicada                                                                                                              |
| US 15     | Eu, como usuário, recebo a cada espaço de tempo(hora,dia) a aplicação de insulina basal (que precisa ser aplicada todo dia)                                                              |
| US 16     | Eu, como usuário, edito a configuração das notificações para receber cada uma de acordo com o tempo desejado                                                                             |
| US 17     | Eu, como usuário, recebo uma notificação a cada espaço de tempo(hora,dia) sobre alimentação para que registre o que ingeri                                                               |
| US 18     | Eu, como usuário, listo todos os meus registros para visualizar minha rotina alimentícia e medicinal                                                                                     |
| US 19     | Eu, como usuário, vejo as informações do meu registro em detalhes a fim de consultar aquilo que preenchi anteriormente                                                                   |
| US 20     | Eu, como usuário, vejo um gráfico dos meus registros a fim de acompanhar minha evolução no tratamento diabético                                                                          |

# Critérios de Aceitação

| Histórias de Usuário                                 | Critérios                                                                                                                                                                                                                                                               |
|------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| US 2 - Visualizar dados cadastrais                   | Visualizar os meus dados em uma página de perfil única Campo de nome, idade , altura, peso, sexo, data de nascimento e email                                                                                                                                            |
| US 3 - Editar dados                                  | O usuário deverá poder editar os campos de idade, altura, peso, email e senha da conta                                                                                                                                                                                  |
| US 4 - Registrar alimentação                         | O usuário deverá registrar as quantidades de alimento de cada refeição registro dos alimentos em qtde de carboidratos, proteínas e gorduras abrir uma janela para o registro ter campos de nome para o alimento, porção, data e horário                                 |
| US 5 - Visualizar intervalo entre refeições          | mostrar quanto tempo faz desde o registro da última refeição ter a informação em uma página separada                                                                                                                                                                    |
| US 6 - Registrar prescrição médica                   | registrar os tipos de insulina abrir janela com as opções disponíveis de insulina para salvar                                                                                                                                                                           |
| US 8 - Registrar aplicação de insulina               | O usuário deverá registrar as aplicações por quantidade de unidades e por tipo de insulina                                                                                                                                                                              |
| US 9 - Visualizar intervalo entre aplicações         | O usuário deverá visualizar o tempo que passou desde sua última aplicação de insulina para não ter excesso de insulina em atividade no seu corpo                                                                                                                        |
| US 10 - Visualizar medição de glicemia               | O usuário deverá visualizar o valor da sua glicemia na última medição                                                                                                                                                                                                   |
| US 11 - Registrar glicemia a cada medição            | O aplicativo deverá registrar o valor da sua glicemia em cada medição para não perder o acompanhamento da rotina do tratamento                                                                                                                                          |
| US 12 - Calcular insulina em caso de hiperglicemia   | O aplicativo deverá ser capaz de realizar um cálculo da quantidade de insulina para caso de hiperglicemia(quando o valor da glicemia está acima do ideal)                                                                                                               |
| US 13 - Receber quantidade de insulina para correção | O aplicativo deverá calcular e informar o usuário a quantidade de insulina ele deve aplicar após uma refeição                                                                                                                                                           |
| US 15 - Receber quantidade de insulina basal         | O aplicativo deverá notificar o usuário da quantidade de insulina basal a ser aplicada. A insulina basal deve ser aplicada todos os dias no mesmo horário para que ela possa agir no corpo no período de tempo certo por ser uma insulina com diferente período de ação |
| US 16 - Editar configurações de notificações         | O usuário deverá ser capaz de editar o tempo de recebimento entre cada notificação de acordo com o tempo desejado(tempo baseado no horário em que o usuário faz suas aplicações)                                                                                        |
| US 17 - Receber lembretes para fazer registros       | O aplicativo deverá enviar lembretes para o usuário não esquecer de registrar a refeição feita                                                                                                                                                                          |

