

![N|Solid](https://raw.githubusercontent.com/Wilkor/img-clonebots/main/logoParseHorizontal.jpeg)


O **Plugin SGP**, foi criado para facilitar a integração com o sistema de provedores SGP. nele você pode contar com duas principais integrações: Segunda vida de boleto e Desbloqueio em confiança.


# Configuração
 Nessa sessão do plugin, você pode fazer um clone de uma versão BETA para PROD, alem de poder levar junto para o outro bot: resource (conteúdos), respostas prontas e gerenciamento de filas. 
 
 Para usar essa funcionalidade é muito simples, basta instalar o CloneBots no seu bot destino, adicionar a chave **HTTP/key** do bot que você deseja clonar no campo "Enter the source bot key" e depois de ter selecionado uma ou mais opções dessa sessão,  é só clicar no botão **Clone** e pronto! o fluxo do bot A vai estar no bot B
 
![N|Solid](https://raw.githubusercontent.com/Wilkor/img-clonebots/main/clone-builder.png)
 
# Merge of Blocks
 A ideia aqui nesta sessão é fazer o clone apenas de um ou mais blocos, por default,  eu deixei alguns blocos pre-setados que poderão ajudar em algum tipo de validação, por exemplo: validação de email, validação de cpf e etc.
 
 Caso queira clonar blocos de um outro bot, você pode pegar a chave **HTTP/Key** do bot origem, inserir no campo **bot key**, depois clicar em **get builder**.
 Bom, realizado o processo acima, basta selecionar o bloco desejado, levar ele parar a caixa a direita e clicar em **Merge**, após isso, o bloco selecionado deve aparecer no bot destino na mesma posição que ele estava no bot origem.
 
![N|Solid](https://raw.githubusercontent.com/Wilkor/img-clonebots/main/merge-of-blocks.png)

# Resource and Builder flow

Esse sessão é restrita para quem cria bots no padrão **chassi**!  

Hoje a **.parse** também tem um processo inovador de criação de fluxo utilizando a plataforma da takeBlip, nós chamamos de chassi, com uma estrutura única e sem muitos blocos, nós adotamos um conceito de que cada bloco tem sua responsabilidade, com isso ganhamos velocidade no desenvolvimento, além dos beneficios que acretidamos que esse modelo nos entrega, são eles:

- Redução de caixinhas, deixando o builder mais objetivo;

- Tracking de forma automática, ou seja, sendo gerado de acordo com a navegação em inputs do usuário (diferente do Tracking automático que esta em configurações);

- Reaproveitamento de bots. Como é usado um chassi que é baseado no recurso, quando quiser trocar a skill do bot, troco apenas a estrutura do resource, e não o bot inteiro;

- trago a ideia de responsabilidade por bloco, ou seja, Requisições é responsável por chamadas a serviços e valida inputs, responsável por tratar alguma informação referente ao input do usuário;

- O chassi esta baseado em multicanal, sendo possível add qualquer outra skill de forma simples;

Video demostrativo:

[![IMAGE_ALT](https://raw.githubusercontent.com/Wilkor/img-clonebots/main/builderFlow2.png)](https://youtu.be/E8YskEEM5Pc)

# Broadcast Desk (Uso em bots Roteadores + WhatsApp instalado)
 Por essa sessão do plugin, podemos utilizar um outro plugin que foi desenvolvido para eviar **notificações ativas pelo Desk** (plataforma de atendimento da takeBlip)
 Aqui você só precisa indicar o template padrão que quer usar e pronto!
 
 obs:Serviço é pago.
 
 ![N|Solid](https://raw.githubusercontent.com/Wilkor/img-clonebots/main/desk-configuration.png)
 
# Send Notification (Uso em bots Roteadores + WhatsApp instalado)
Nessa guia do plugin, ainda beta, você pode enviar notificações ativa para os clientes assim como é feito no próprio plugin de broadcast que já existe na plataforma, porém ao inviar pelo **CloneBots**, você pode setar variaveis no extras do contato, te dando mais **flexibilidade e estrategia** na hora de recepcionar essa mensagem.

![N|Solid](https://raw.githubusercontent.com/Wilkor/img-clonebots/main/Send-notification.png)


