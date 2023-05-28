# Critérios de Aceitação 

## Histórico de Revisão

| Data       | Versão | Descrição                                        | Autor            |
|------------|--------|--------------------------------------------------|------------------|
| 17/05/2023 | 1.0    | Construção dos Critérios de Aceitação            | Felipe Guimarães |
| 27/05/2023 | 1.1    | Edição dos Critérios de Aceitação das US's 1 a 5 | Igor Abreu       |

## Tabela de Critérios de Aceite de Requisitos 

Os critérios de aceite abaixo destacados, serão aqueles trabalhados durante as Sprints do Projeto e servem para confirmar aquilo que é pedido em cada requisito. Todos os critérios podem ser encontrados nessa seção :

| Numero      | Nome                     | Criterios                                                                                                                                                       |   |   |
|-------------|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|---|---|
| US 1        | Cadastro de Usuário      | - Os campos obrigatórios para cadastro devem ser: Nome completo, Email e senha;                                                                                 |   |   |
|             |                          | - Os campos obrigatórios de prescrição diabética devem ser: o tipo de insulina, a quantidade usada pra correção e a proporção da contagem                       |   |   |
|             |                          | - Deve ser verificado se o email existe;                                                                                                                        |   |   |
|             |                          | - Para acessar o cadastro o usuário deve visualizar um botão pela tela inicial do aplicativo;                                                                   |   |   |
|             |                          | - A senha precisa ter um comprimento mínimo de 8 caracteres;                                                                                                    |   |   |
|             |                          | - Necessário confirmar senha, o sistema deverá passar quando ambos os campos de senha estiverem iguais;                                                         |   |   |
|             |                          | - Exibir mensagem de erro caso o e-mail já tenha sido cadastrado;                                                                                               |   |   |
|             |                          | - Direcionar para a tela de login após o cadastro ser bem-sucedido;                                                                                             |   |   |
| US 2        | Autenticação de Usuário  | - O usuário deve ter acesso à tela de login;                                                                                                                    |   |   |
|             |                          | - Os campos a serem preenchidos devem ser: Email, Senha;                                                                                                        |   |   |
|             |                          | - O sistema deve verificar se o e-mail inserido está cadastrado no sistema;                                                                                     |   |   |
|             |                          | - O sistema deve verificar se a senha está correta e seja associada ao e-mail inserido;                                                                         |   |   |
|             |                          | - Caso negativo: Exibir mensagem de erro;                                                                                                                       |   |   |
|             |                          | - Caso positivo: O usuário deve ser autenticado e direcionado para a tela principal do sistema;                                                                 |   |   |
|             |                          | - O usuário deve ter acesso a opção de recuperação de senha caso a tenha esquecido, fornecendo um mecanismo de redefinição da mesma;                            |   |   |
|             |                          | - Na tela de login, o usuário deve ter acesso à uma opção que encaminha para o cadastro;                                                                        |   |   |
| US 3        | Visualizar perfil        | - Ter uma página unica do perfil;                                                                                                                               |   |   |
|             |                          | - exibir dados pessoais(nome e email);                                                                                                                          |   |   |
|             |                          | - exibir dados médicos;                                                                                                                                         |   |   |
| US 4        | Editar  perfil           | - Deverá ter um perfil ou uma área onde o usuário possa acessar e editar seus dados pessoais;                                                                   |   |   |
|             |                          | - Os dados a serem editáveis devem ser: Nome, Email e Senha                                                                                                     |   |   |
|             |                          | - O sistema deve permitir que o usuário salve as alterações feitas;                                                                                             |   |   |
|             |                          | - O sistema deve validar os campos modificados e entregar uma resposta imediata caso algum campo esteja preenchido corretamente;                                |   |   |
|             |                          | - Para modificar a senha, deverá ter uma dupla confirmação;                                                                                                     |   |   |
|             |                          | - Exibir uma mensagem de erro caso alguma informação tenha sido preenchida erroneamente;                                                                        |   |   |
|             |                          | - Após as informações serem salvas com sucesso, apresentar uma mensagem de sucesso e direcionar para o perfil do usuário com as informações já atualizadas;     |   |   |
| US 5        | Deletar Perfl de Usuário | - O usuário deve ter acesso à uma opção de exclusão de perfil no sistema;                                                                                       |   |   |
|             |                          | - A opção deve estar clara e fácil de ser encontrada;                                                                                                           |   |   |
|             |                          | - O usuário deve receber um aviso explícito que a exclusão permanente resultará na perda irreversível de todas as informações e dados associados ao seu perfil; |   |   |
|             |                          | - Para confirmar a exclusão, o usuário deverá colocar a sua senha;                                                                                              |   |   |
|             |                          | - O sistema deverá fazer uma dupla confirmação da exclusão;                                                                                                     |   |   |
|             |                          | - Após confirmar a exclusão, o sistema deverá exibir uma mensagem de confirmação e encaminhar para a tela inicial de login;                                     |   |   |

