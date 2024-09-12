# Instalação do 4Med no SAP Business One

Inicialmente, é necessário instalar o addon 4Med no SAP Business One (Client). Este procedimento deve ser realizado primeiro, pois, sem essa configuração, o serviço não poderá ser iniciado.

Para realizar a instalação do 4Med, baixe o software através do link fornecido. Normalmente, o arquivo está compactado no formato `.zip`. Descompacte o arquivo no diretório onde o SAP Business One está instalado. Deverão existir três arquivos:

- O arquivo ARD do addon;
- O instalador do 4Med (executável);
- O instalador do serviço do 4Med.

![Configurações Gerais](imagens/Instalador.png)

## Instalação do Addon 4Med no SAP Business One

A instalação do addon segue o modelo padrão para instalações de addons no SAP Business One.

> **Atenção:**  
> Certifique-se de que o usuário do Windows que está sendo utilizado possui privilégios para instalar softwares.

1. Conecte-se ao SAP Business One com um Superusuário e acesse: **Administração → Add-Ons → Administração de Add-On**.

![Configurações Gerais](imagens/Administracao_addon.png)

2. Na tela exibida, clique no botão **Registrar Add-On**, localizado no canto inferior esquerdo.

![Configurações Gerais](imagens/Registro_addon.png)

3. Selecione o arquivo ARD que foi descompactado anteriormente no campo **Arquivo de Dados de Registro**.

![Configurações Gerais](imagens/Registro_addon2.png)

4. O pacote de instalação será carregado automaticamente. Verifique se isso ocorreu e clique em **Ok**.

![Configurações Gerais](imagens/Registro_addon3.png)

5. O SAP Business One apresentará os dados do 4Med que está sendo instalado. Selecione um grupo padrão que não seja "Desativado", pois o 4Med só será instalado se estiver ativado. No exemplo, definimos como "Manual". Selecione o checkbox na coluna **Ativo**, clique em **Atualizar** e, em seguida, em **Atualizar e Ok**.

![Configurações Gerais](imagens/Registro_addon4.png)

> **Dica:**  
> Em alguns ambientes, é necessário selecionar **Forçar Instalação**, pois o addon pode não aparecer para ser instalado.

> **Dica:**  
> Normalmente, define-se o grupo padrão por usuário. Para isso, utilize a aba **Add-Ons por Usuário** para realizar essa configuração.

6. Após registrar o addon no SAP Business One, é necessário instalar o 4Med de fato. Para isso, acesse: **Administração → Add-Ons → Administrador de Add-On**.

![Configurações Gerais](imagens/Administrador_addon.png)

7. Na tela exibida, clique na aba **Add-Ons Pendentes**, onde será exibida uma lista de addons disponíveis para instalação. Selecione o 4Med e clique em **Instalar**.

![Configurações Gerais](imagens/Instalar.png)

> **Dica:**  
> Caso não apareça nenhum addon, retorne à tela de registro e selecione **Forçar Instalação**. Se o problema persistir, reinicie o SAP Business One.

8. O instalador do 4Med será iniciado. Siga os procedimentos padrão de instalação para softwares Windows (Next → Next → Install → Finish).

![Configurações Gerais](imagens/Instalacao.png)

![Configurações Gerais](imagens/Instalacao2.png)

9. Se tudo ocorrer corretamente, o SAP Business One copiará o 4Med para a lista de **Add-Ons Instalados**. Clique em **Sim** para confirmar o êxito na instalação.

![Configurações Gerais](imagens/Mensagem_sistema.png)

10. Para iniciar o addon, basta selecioná-lo, clicar em **Início** e, em seguida, em **Ok**.

Com a instalação e execução do addon 4Med concluídas, o ícone correspondente será habilitado no menu principal do SAP Business One.

![Configurações Gerais](imagens/Iniciar_addon.png)

![Configurações Gerais](imagens/Addon_iniciado.png)

[Próximo -> Instalação Serviço](4Med-05-Instalação_Serviço)