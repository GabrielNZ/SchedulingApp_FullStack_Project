# 📆 AppAgendamento Project / SchedulingApp Project
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/GabrielNZ/FinalProject-AppAgendamento/blob/main/LICENSE)

### [English Version](./READMEus.md)

## Estrutura do Projeto

<img width="600" height="450" alt="image" src="https://github.com/user-attachments/assets/ca259c05-d02e-406f-bbc3-84220925078a"/>

# PT-BR 🇧🇷

### Sobre o projeto

Antes de começar a minha história universitária, desejava aplicar em um projeto tudo que havia aprendido nesse 1 ano de estudo. **Aqui está!**
Após 3 meses de programação diária, apresento meu primeiro projeto **Full Stack**.

Consiste em uma aplicação na qual através de um dashboard, clientes e prestadores podem organizar o agendamento de serviços, isto é:
- Prestador -> Cria serviço e disponibilidade na semana.
- Cliente -> Solicita agendamento de um serviço em algum horário disponível.

**Explicação mais profunda abaixo e no vídeo de demonstração**

### ⚙️ Back end
- Acredito que consegui aplicar de uma forma satisfatória meu principal conhecimento (Backend).
  
- A lógica do projeto foi criada por mim; a utilização de IA foi exclusivamente para otimização de código e aplicar conhecimentos novos:

> Ex:
> Meu conhecimento de JWT utilizado em projetos anteriores ficou ultrapassado para o projeto,
> sendo assim, utilizei da IA para atualizar meu conhecimento.
- [Como o BackEnd está estruturado?](./STRUCTUREbackendptbr.md)

### ✨ Front end
- Ainda não consegui adquirir conhecimento suficiente para usar um framework no front-end, por isso decidi aplicar apenas o que eu sabia (HTML, CSS & JS).
- Ao analisar o código é fácil notar a desorganização e a utilização de ferramentas simples e diretas, porém levando em conta que estudei pouco da área e meu foco é no back-end,
considero uma grande vitória o simples fato do código ser funcional.

Sem conhecimento ainda em um framework, utilizei fetch para as requisições REST e manipulação do HTML com JS para o site.

- [Demonstração Projeto Agendamento ( PT-BR )](https://www.youtube.com/watch?v=pPAIpPzvmSo) (Áudio e vídeo com mais qualidade. GitHub limita para 10MB)

https://github.com/user-attachments/assets/94874ef1-c1d9-445e-afd3-8b43b765b0be


# 🚦 Como Executar o Projeto
### 🛠 Pré-requisitos
- Git
- VSCode (Live Server)
- Docker
### 🚀 Como rodar na minha máquina?
1. Clone o repositório: `git clone https://github.com/GabrielNZ/FinalProject-AppAgendamento.git` && `cd FinalProject-AppAgendamento`.
2. Configure as variaveis de ambiente no arquivo `.env`.
3. Insira no console `docker compose up -d --build`<br>
(A primeira inicialização pode demorar alguns minutos.)
4. Abra a pagina `Frontend/html/loginpage.html` através da extensão `Live Server` no VSCode.

### Obs:
Caso ocorra um erro relacionado à `versao minima do Docker`:
1. Abra seu Docker Desktop
2. Vá na aba de `Configurações` > `Docker Engine` > e adicione esse linha: `"min-api-version": "1.24"`
<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/56b5e336-1ac2-4f8d-8d74-863fc1fe3d34" />

## 🎯 Tecnologias
### Back end
- Java
- JPA
- Spring Boot
- Spring Web
- Spring Security
- Spring Cloud
- JWT
### Front end
- JavaScript
- Html
- Css
### Implementation
- DataBase: MySQL
- Messaging
  - RabbitMQ
  - AMQP
- JavaMailSender
- Docker
## Autor

Gabriel Nicolodi Zimmermann


[https://www.linkedin.com/in/gabriel-n-zimmermann-aba618338/]
