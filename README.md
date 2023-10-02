# Aplicativo de Chat com Firebase

Bem-vindo ao repositório do aplicativo de chat com Firebase! Este aplicativo possibilita a funcionalidade de chat em tempo real usando o Firebase como backend. Abaixo está uma lista de arquivos-chave e suas funcionalidades:

## Arquivos de Atividade

- `ChatActivity.java`: A atividade principal para conversas de chat individuais.
- `LoginOtpActivity.java`: Gerencia a autenticação do usuário usando OTP.
- `LoginPhoneNumberActivity.java`: Gerencia o login do usuário com base no número de telefone.
- `LoginUsernameActivity.java`: Controla o login do usuário usando um nome de usuário.
- `MainActivity.java`: O ponto de entrada do aplicativo e o hub de navegação principal.
- `SearchUserActivity.java`: Permite aos usuários procurar outros usuários para iniciar conversas.
- `SplashActivity.java`: Exibe uma tela de splash enquanto o aplicativo é inicializado.

## Arquivos de Fragmento

- `ChatFragment.java`: Gerencia a interface de chat e a lógica dentro da atividade de chat.
- `ProfileFragment.java`: Lida com a exibição e edição do perfil do usuário.
- `SearchUserFragment.java`: Exibe os resultados da pesquisa de usuários e opções para iniciar um chat.

## Arquivo de Serviço

- `FCMNotificationService.java`: Integra o Firebase Cloud Messaging para notificações push.

Sinta-se à vontade para explorar esses arquivos para entender a estrutura do aplicativo e como os diferentes componentes interagem. O aplicativo utiliza a autenticação do Firebase, o banco de dados em tempo real e o Firebase Cloud Messaging para fornecer funcionalidade de chat contínua.
