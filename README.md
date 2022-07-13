# 💡 MENSAGERIA DE SMS 🚀#

✔️⚠️🍎🤖🧐📚🛠✅🛑◀️😳👶🏻🎨🤔📜🔢🧶🥳🥰🧠🚫🔒📺📄👉👩‍💻🐛💯

* ⭐️ O objetivo deste trabalho é apresentar a descrição do projeto arquitetural de
uma aplicação de mensageira baseada em micro-serviços.

Os objetivos específicos propostos são:
* ⭐️ Realizar um estudo de mercado sobre a área de negócio da aplicação
proposta;
* ⭐️ Descrever os requisitos técnicos da aplicação de forma resumida, clara e
objetiva;
* ⭐️ Descrever os requisito funcionais do serviço a ser desenvolvido;
* ⭐️ Descrever a arquitetura do serviço através de diagramas;
* ⭐️ Avaliar os serviços de terceiros que serão utilizados para desenvolver a
solução.
* ⭐️ Avaliar o custo e tempo necessários para o desenvolvimento da solução
final.
* ⭐️ Coletar resultados e evidências da prova de conceito.
* ⭐️ Apresentar conclusões sobre a solução proposta.

### 🤖 Especificação Arquitetural da solução ###
* Esta seção apresenta a especificação básica da arquitetura da solução a ser
desenvolvida, incluindo diagramas, restrições e requisitos definidos pelo autor, tal que
permite visualizar a macro arquitetura da solução.

### 👉 Restrições Arquiteturais ###

* R1: O software deve ser desenvolvido em Java, com o framework Spring Boot;
* R2: As APIs devem seguir o padrão ReSTful.
* R3: O portal de parametrização dos sms, precisa utilizar a linguagem typescript e o
framework angular.
* R4: A arquitetura deve utilizar o padrão de micro-serviços.
* R5: A API para disparo de sms será utilizada de terceiros.
* R6: Todos os softwares utilizam o padrão clean architecture.
* R7: Todos os micro serviços se comunicarão através de filas.
* R8: Todos os micro-serviços terão seu próprio banco de dados, caso precise
armazenar algum tipo de informação.

### 🧐 Requisitos Funcionais ###

* RF01 O sistema deve permitir o cadastramento de campanhas de sms 
* RF02 Deve permitir a parametrização do sms através do portal web 
* RF03 Deve permitir o disparo de sms
* RF04 Deve permitir o agendamento de disparos via sms 
* RF05 Deve permitir a aprovação de campanhas sms enviadas pelos clientes
* RF06 Inclusão, exclusão e alteração de mensagens sms
* RF07 Deve permitir o disparo manual de um sms 
* RF08 Inclusão, exclusão e alteração de notificações push 
* RF09 Deve permitir o agendamento de disparos via push 
* RF10 Deve permitir a aprovação de campanhas push enviadas pelos clientes

## 📚 Requisitos Não-funcionais ##

* RNF01 O sistema deve ser apresentar disponibilidade 24 X 7 X 365 A
* RNF02 O sistema deve ter o design responsivo M
* RNF03 O sistema deve ter tolerância a falhas A
* RNF04 O sistema deve ser capaz de gerar alertas caso ocorra indisponibilidades. A
* RNF5 O sistema deve permitir monitorar a saúde dos microsserviços M
* RNF6 O sistema deve permitir escalonar os micro serviços horizontalmente M

## 🥰 Mecanismos Arquiteturais ##

* ImplementaçãoProjeto Integrado – Engenharia de Software - PMV
* Persistência ORM Hibernate
* Front end Single Page Application Angular
* Back end API/ Consumer and Producer Spring Boot
* Integração SMS Twilio
* Log do sistema Horário, Nível do Log, Nome da thread, nome do logger e a mensagem Log4J
* Teste de Software Unit Test Junit
* Deploy CI/CD Azure Devops
* Direcionamento de Rotas Gateway Server API Azure
* Monitoramento Micro-serviços Spring Admin
* Comunicação Event Bus Service Bus
* Documentação de API Open API Swagger

## 📜 Prova de Conceito (PoC) ##

Integrações entre Componentes

* Mock Wireframes :

* Front-end

https://www.figma.com/proto/TABuc5qkiP2NoLlyoeRhFi/One-Message?node-id=27%3A3188&scaling=min-zoom&page-id=4%3A730&starting-point-node-id=27%3A1392

* Mock API:
* Back-end

https://app.swaggerhub.com/apis-docs/onemessage/message/1.0.0

https://app.swaggerhub.com/apis-docs/onemessage/campaign/1.0.0

https://app.swaggerhub.com/apis-docs/onemessage/approval/1.0.0

https://app.swaggerhub.com/apis-docs/onemessage/subscribe/1.0.0

## 🔢🧶 Vídeo de apresentação final Completo ##

https://www.canva.com/design/DAE0gkQfJ1w/eqkxwSrlljh9L0RcsS3V2g/watch?utm_content=DAE0gkQfJ1w&utm_campaign=designshare&utm_medium=link&utm_source=homepage_design_menu



## 📺 Saiba Mais ##

* 💥[Documentção](https://docs.google.com/document/d/1ulTZisPwW6xXVLBVsH3wfujLCOtNbV4T/edit?usp=sharing&ouid=102321577832590230807&rtpof=true&sd=true)
