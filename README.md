# Cloud Service AI
Estudos sobre Azure AI Search/Azure Cognitive Search  e IA Generativa com Copilot e OpenAI - DIO


## Azure AI Search / Azure Cognitive Search
O Azure Cognitive Search é um serviço onde oferece recursos de pesquisa que permite que os desenvolvedores realizem queries personalizadas facilitando a localização de informações relevantes em grandes volumes de dados.

Recursos usados: Azure AI Search, Azure AI services, Storage account

**Azure AI Search**: idexaçao e colsulta.

**Azure AI services**: recurso de inteligencia artificial para gerar insights sobre os dados.

**Storage account**: armazenar os dados/documentos brutos (arquivos; tabelas; objetos).

*Search explorer*: usado para realizar as consultas, podendo escolher retornar em Query ou JSON View.

Ex.: 
{
 "search": "sentiment:'negative'",
 "count": true
}
*Irá retornar todos os dados onde a analize do sentimento foi negativa.*

OBS1: Azure AI services deve estar na mesma localidade que o seu recurso do Azure AI Search.
OBS2: Permitia o acesso anônimo do Blob na area do Storage account

## Azure AI Search / Azure Cognitive Search