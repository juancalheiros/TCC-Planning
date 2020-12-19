# Arquitetura

>## Como será a arquitetura?
>Princípios:
> - Escalabilidade
> - Disponibilidade
> - Resiliência
> - Independente, autônomo
> - Governança descentralizada
> - Isolamento de falha
> - Auto-Provisioning
> - Entrega contínua por meio de DevOps

Tendo em vista esses princípios a *Arquitetura de microsserviços* (Microservices pattern) é a mais adequada para esse desenvolviemnto.

Este padrão utiliza múltiplos serviços e componentes para desenvolver uma estrutura modular favorecida. 

Hoje, é um dos modelos preferidos dos desenvolvedores e arquitetos de software por possibilitar a escalabilidade e independência dos módulos – que até podem utilizar diferentes linguagens e programações.

> Utilizaremos uma *liguagem Hibrida*, pois utilizaremos o mesmo app em diferentes devices. Além de ter funcionalidades que não não nativas.

#### Qual banco?
Será utilizado *mongoDB*, caso haja necessidade.


#### Como será o back-end ?

 Pela minha pesquisa o modelo que mais se enquadra é a de API BFF Gateway, pois segue padrões de ligação com os microserviços e poderá ser aproveita para o nosso princípio de escalabilidade. 

 ![custom-service-api-gateway](/media/images/custom-service-api-gateway.png)

#### Qual linguagem será desenvolvido o back, tendo em vista os micros serviços?

Realizei pesquisas de performace, vale a pena conferir no link a seguir: 
[Teste de performace Asp .net core Vs GoLang](https://stefanprodan.com/2016/aspnetcore-vs-golang-data-ingestion-benchmark/)
 > - GoLang
 > Vantagens: Apresentou um desempenho maior frente ao c#
 > Desvantagens: Curva de aprendizado longa, poucas referências de api nesse modelo em go (eu não encontrei nenhuma nessa pesquisa).
-----------------
 > - .Net (C#)
 > Vantagens: Fornece maior segurança e desempenho de tipo pois suporta os métodos e tipos genéricos. Curva de aprendizado menor, referências de desenvolvimento de api bff desenvolvidas nessa liguagem.
 > Desvantagens: Menos Performático, frente ao Golang. 


#### Qual Framework?

FLutter ou React Native

Favor elencar pós e contras de cada uma: 
>
>

[buil and distribuibute in flutter](https://medium.com/@levelfivecoder/how-to-build-sign-and-distribute-your-flutter-android-application-using-azure-devops-and-appcenter-965382b85b8b)


#### Git lab ou AzureDevops
[Project AzureDevOps da Equipe](https://dev.azure.com/coding-jmn/)

OBS.: Logar com a conta institucional da Unicarioca

| Título | Links Úteis |
-------------------------
[Caso de uso de referência](https://pjbhqxbjgrrityj5z56wk3smzi--www-thoughtworks-com.translate.goog/insights/blog/bff-soundcloud)
[Referencia-architecture](https://github.com/wso2/reference-architecture/blob/master/api-driven-microservice-architecture.md)
[buil and distribuibute in flutter](https://medium.com/@levelfivecoder/how-to-build-sign-and-distribute-your-flutter-android-application-using-azure-devops-and-appcenter-965382b85b8b)
[Configuring Cl/CD with YAML](https://www.azuredevopslabs.com/labs/azuredevops/yaml/#task-3-adding-a-yaml-build-definition)
[Create your firt pipeline](https://docs.microsoft.com/en-us/azure/devops/pipelines/create-first-pipeline?view=azure-devops&tabs=java%2Ctfs-2018-2%2Cbrowser)
[Kubernetes](https://kubernetes.io/)
[DockerHub](https://hub.docker.com/)
[azure devops](https://azure.microsoft.com/en-us/services/devops/)