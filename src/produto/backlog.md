# Backlog do Produto



App PancreAmigo

Backlog do Produto

Estão dispostos os requisitos a serem trabalhados pela equipe, separados por temas, épicos e histórias de usuário. Eles foram organizados de acordo com a prioridade do cliente e viabilidade entre eles, já que vários requisitos dependem de outros para existir.

Temas

T1 - Dados Pessoais
T2 - Dados Médicos
T3 - Regras de Negócio

Épico

E1 - Cadastramento
E2 - Alimentação
E3 - Dados sobre Insulina
E4 - Dados sobre Glicemia
E5 - Indicações
E6 - Notificações
E7 - Gráficos





Histórias de Usuário

VN: Valor de negócio
Ve: Viabilidade
C: Complexidade

A pontuação do valor de negócio, viabilidade e complexidade foram definidos em uma escala de 1 a 3, e a pontuação total foi obtida multiplicando VN por Ve e dividindo por C.


Tema
Épico
US
História de Usuário
VN
Ve
C
Total
T1
E1
US1
Eu, como usuário, preciso cadastrar meus dados para que as minhas informações sejam salvas corretamente 
3
3
1
9
US2
Eu, como usuário, desejo visualizar um perfil com todos meus dados cadastrados para verificação e exibição
2
4
1
8
US3
Eu, como usuário, desejo editar quaisquer dados de cadastro como nome, email, senha, data de nascimento, altura, peso ++ para que eu possa corrigir possíveis alterações
3
4
2
6
E2
US4
Eu, como usuário, preciso registrar aquilo que como para controlar a quantidade de carboidrato, proteína e gordura, itens que interferem diretamente no tratamento


3
 2
 2
3
US5
Eu, como usuário, preciso ter salvo aquilo que consumi para poder tomar melhores decisões nas horas seguintes as refeições 
3
 3
2
4,5
US6
Eu, como usuário, preciso ter registrado o tempo exato desde a última refeição para verificar o tempo para comer novamente
2
 3
 2
3
T2
E3
US7
Eu, como usuário, desejo ter os dados da minha prescrição cadastrados para que o aplicativo possa fazer os cálculos de forma correta
3
3 
1
9
US8
Eu, como usuário, preciso ser capaz de registrar quando fizer uma aplicação de insulina 
2
 2
 1
4
US9
Eu, como usuário, preciso ser capaz de diferenciar os registros de aplicação por quantidade de unidades e por tipo de insulina 
2
 3 
 1
6
US10
Eu, como usuário, preciso ser capaz de ver quando fiz a última aplicação para não ter excesso de insulina em atividade 


2
 2
 2
2
E4
US11
Eu, como usuário, preciso ser capaz de ver facilmente o valor da última medição de glicemia


3
 3
 1
9
US12
Eu, como usuário, preciso que os valores de glicemia sejam exibidos para um bom acompanhamento das decisões a curto e longo prazo 
3
3
2
4,5
US13
Eu, como usuário, preciso registrar os meus valores de glicemia no app a cada aferição 
3
3
1
9
T3
E5
US14
Eu, como usuário, preciso ser capaz de calcular a quantidade de insulina a ser aplicada em caso de hiperglicemia (quando o valor da glicemia está acima do ideal) 


3
 3
 2
4,5
US15
Eu, como usuário, gostaria de receber a quantidade de insulina a ser aplicada para corrigir uma refeição com base nos dados que inseri 
3
 2
 2
3
US16
Eu, como usuário, desejo ter acesso a uma estimativa do valor da minha hemoglobina glicada 
1
 2
3
0,667
E6
US16 
Eu, como usuário, gostaria de receber uma notificação a cada espaço de tempo(hora,dia) sobre a aplicação de insulina basal (que precisa ser aplicada todo dia) 
4
 2
2
4
US17
Eu, como usuário, gostaria devo editar a configuração das notificações para receber cada uma de acordo com o tempo desejado
2
3
2
3
US18
Eu, como usuário, gostaria de receber uma notificação a cada espaço de tempo(hora,dia) sobre alimentação para que registre o que ingeri
4
2
2
4
E7
US19
Eu, como usuário, desejo poder consultar todos os meus registros separados por data e horário 


2
2
2
2
US20
Eu, como usuário, desejo ter as informações que insiro compiladas de forma gráfica, para permitir uma visualização mais ampla


2
 1
2
1





Requisitos não-funcionais

	RNF001 - Implementação: O back-end e o front-end do produto deverá ser feito utilizando a tecnologia Flutter
	RNF002 - Suportabilidade: O produto estará disponível para smartphone android a partir da versão  5.0
	RNF003 - Confiabilidade: O produto deverá guardar os dados cadastrados do usuário respeitando a Lei nº 13.709/2018, conhecida como Lei Geral de Proteção de Dados (LGPD)
RNF004 - Usabilidade: O produto deverá ter uma interface limpa, orientando de forma didática a usabilidade do produto. Além disso, por pedido da cliente, a interface deve ser azul e laranja.

	








Mínimo Produto Viável

MVP1

O objetivo desse MVP é alcançar o necessário para que o usuário consiga registrar e manipular suas informações.


Requisito
Descrição
US1
Eu, como usuário, preciso cadastrar meus dados para que as minhas informações sejam salvas corretamente 


US2
Eu, como usuário, desejo ter os dados da minha prescrição cadastrados para que o aplicativo possa fazer os cálculos de forma correta
US3
Eu, como usuário, preciso registrar os meus valores de glicemia no app a cada aferição 
US4
Eu, como usuário, preciso que os valores de glicemia sejam registrados para um bom acompanhamento das decisões a curto e longo prazo 
US5
Eu, como usuário, preciso registrar minha alimentação para controlar a quantidade de carboidrato, proteína e gordura, itens que interferem diretamente no tratamento


US6
Eu, como usuário, preciso ter salvo aquilo que consumi para poder tomar melhores decisões nas horas seguintes as refeições 
US7
Eu, como usuário, preciso ser capaz de registrar quando fizer uma aplicação de insulina 
US8
Eu, como usuário, preciso ser capaz de diferenciar os registros de aplicação por quantidade de unidades e por tipo de insulina 
US9
Eu, como usuário, preciso ser capaz de ver quando fiz a última aplicação para não ter excesso de insulina em atividade 


US10
Eu, como usuário, preciso ter registrado o tempo exato desde a última refeição






MVP2

O objetivo do MVP é conseguir ter acesso aos registros das informações inseridas, para habilitar o uso com o intuito de monitoramento a longo prazo. Além disso, esse MVP também traz a adição da manipulação de dados de forma direta, sem que o usuário precise inserir tudo manualmente.


Requisito
Descrição
US11
Eu, como usuário, preciso ser capaz de ver facilmente o valor da última medição


US12
Eu, como usuário, preciso ser capaz de calcular a quantidade de insulina a ser aplicada em caso de hiperglicemia (quando o valor da glicemia está acima do ideal) 


US13
Eu, como usuário, gostaria de receber a quantidade de insulina a ser aplicada para corrigir uma refeição com base nos dados que inseri 
US14 
Eu, como usuário, gostaria de receber uma notificação diária sobre a aplicação de insulina basal (que precisa ser aplicada todo dia) 
US15
Eu, como usuário, desejo poder consultar todos os meus registros separados por data e horário 


US16
Eu, como usuário, desejo ter as informações que insiro compiladas de forma gráfica, para permitir uma visualização mais ampla


US17
Eu, como usuário, desejo ter acesso a uma estimativa do valor da minha hemoglobina glicada 





