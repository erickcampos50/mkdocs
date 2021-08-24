# Como importar configurações do aplicativo manualmente

## Apresentação

Neste guia você aprenderá como realizar a inserção do endereço do servidor e das credenciais (login e senha) do aplicativo manualmente. Essa etapa é fundamental para que possa ter acesso aos dados dos sensores.

Há também a opção de realizar este processo de forma um pouco mais automatizada através das instruções presentes em [link](app-credenciais-auto.md)



### Nota importante

Por questões de segurança as credenciais (login e senha) não são disponibilizadas pelo site, pois elas fornecem acesso a **todos os dados e aos controles dos alarmes**, por isso é preciso solicitá-las por email. 

Para requerer suas credenciais, envie um email para [erick.campos@ufjf.edu.br](mailto:erick.campos@ufjf.edu.br)

## Instalando o aplicativo

O aplicativo utilizado para acessar os dados é o **IoTMQTT-Panel**, que pode baixado na loja de aplicativos do Google através deste [link](https://play.google.com/store/apps/details?id=snr.lab.iotmqttpanel.prod) ou pode ser baixado direto na loja de aplicativos buscando por IoTMQTT-Panel (não existe versão disponível para iPhone), como pode ser visto abaixo:


![img](videos\baixando aplicativo.gif)


## Configurando o aplicativo

Após a instalação vem a etapa de inserção das configurações do aplicativo para acessar o servidor que permitirá acesso a todos os dados dos sensores.

Ao iniciar o aplicativo pela primeira vez surgirá uma tela com um botão para criar uma nova conexão. Clique em **SETUP A CONNECTION** e preencha os campos conforme as instruções abaixo.

![img](images\setup a connection.png)



!!! info "Inserindo os dados do servidor"
    A tela seguinte é onde efetivamente serão inseridos os dados de acesso (incluindo seus dados de login e senha secretos recebidos por email)

    **Connection name:** Servidor 1 *(este nome pode ser modificado à vontade)*

    **Cliend ID:** Deixe este campo em branco

    **Broker Web/IP Address:** ec2-18-117-228-132.us-east-2.compute.amazonaws.com *(este é o endereço do servidor)*

    **Port number:** 1883

    **Network protocol:** TCP *(não confundir com TCP SSL)*




![img](images\add a connection.png)


!!! info "Inserindo uma Dashboard"
    Clique em no botão + ao lado de **Dashboard list** e quando aparecer a caixa de diálogo, digite **Painel**. Esse é apenas um nome provisório, em uma etapa futura você será informado de como incluir o verdadeiro Painel/Dashboard.


![img](images\Dashboard list.png)


!!! info "Dados do usuário"
    Clique em **Additional options** para que se revelem opções extras, que serão necessárias para inserir seus dados de login e senha exclusivos. Para receber os seus dados, solicite por email em [erick.campos@ufjf.edu.br](mailto:erick.campos@ufjf.edu.br).

    Os dados que receberá são exclusivos e não devem ser compartilhados com ninguém. No tutorial em video disponível na seção [Vídeo completo](#video_completo) as credenciais **username: user** e **Password: tutorial** foram utilizados apenas para criar o tutorial e não são mais válidos.

    Insira o login recebido em **username** e a senha recebida em **password**

    Os campos **Connection timeout** e **Keep alive** devem permanecer em branco

    Após finalizar clique em **Create**. Se nenhum campo obrigatório foi esquecido em branco, a tela de configuração deverá fechar.


![img](images\additional options.png)


Após isso o seu aplicativo estará configurado para importarmos o painel de controle com todas as opções de visualização de dados, mas antes precisamos realizar um teste básico para garantir que tudo foi configurado corretamente.

Acesse a nova conexão que foi criada clicando diretamente sobre ela e uma tela com as opções **Clone a panel** e **Add a panel** surgirá. Após isso clique sobre o ícone de setas no menu superior para solicitar que o aplicativo se conecte ao servidor (existem outras formas, mas essa é a mais fácil). 

![img](images\testando conexao.png)

Se tudo estiver corretamente configurado, um ícone de núvem vermelha surgirá em no máximo 10 segundos indicando o sucesso da conexão.


### Vídeo tutorial da configuração do aplicativo

Para auxilair o processo de configuração, foram feitos tutoriais em vídeo que podem ser acessados abaixo no formato GIF (menor resolução e arquivo menor) e vídeo em alta qualidade (aprox. 2MB).

Caso queira baixá-los basta clicar em [GIF](videos\configurando aplicativo.gif) e [VÍDEO](videos\configurando aplicativo.webm)

#### GIF 
![img](videos\configurando aplicativo.gif)


#### VÍDEO
![type:video](videos\configurando aplicativo.webm)

