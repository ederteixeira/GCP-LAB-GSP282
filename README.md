# Google Cloud Computing
## Laboratório: GSP282
### Configuração da API DIALOGFLOW

Para habilitar a API do Dialogflow em seu projeto do Google Cloud, siga estas etapas:

    Acesse a página inicial do seu projeto no Google Cloud.

    Navegue até a seção "API & Services" (APIs e Serviços) no menu.

    Selecione a opção "Biblioteca" (Library).

    Na página Biblioteca, procure por "Dialogflow API" na barra de pesquisa.

    Selecione a API "Dialogflow API" nos resultados da pesquisa.

    Clique no botão "Enable" (Habilitar) para ativar a API em seu projeto.

Habilitando via CLI.

    Acesse o cloud shell do seu projeto no Google Cloud.
    
    gcloud auth login

    gcloud config set project ID_DO_PROJETO (substitua pelo ID do seu projeto).

    gcloud services enable dialogflow.googleapis.com

