# Google Cloud Computing
## Laboratório: GSP282
### Configuração da API DIALOGFLOW

Para habilitar a API do Dialogflow em seu projeto do Google Cloud, siga estas etapas:

1- Acesse a página inicial do seu projeto no Google Cloud.
2- Navegue até a seção "API & Services" (APIs e Serviços) no menu.
3- Selecione a opção "Biblioteca" (Library).
4- Na página Biblioteca, procure por "Dialogflow API" na barra de pesquisa.
5- Selecione a API "Dialogflow API" nos resultados da pesquisa.
6- Clique no botão "Enable" (Habilitar) para ativar a API em seu projeto.

Habilitando via CLI.

1- Acesse o cloud shell do seu projeto no Google Cloud e autorize o acesso.
    
    gcloud auth login
    
2- Configure para o seu pojeto (substitua ID_DO_PROJETO pelo ID do seu projeto.)
    
    gcloud config set project ID_DO_PROJETO
3- Ativando via CLI

    gcloud services enable dialogflow.googleapis.com

