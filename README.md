<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/sistemas-de-informacao">Sistemas de Informação</a></h3>

# Projeto de Prática Profissional em ADS
## Grupo: TCC
### Trabalho de conclusão de curso para Análise e Desenvolvimento de Sistemas - Mackenzie

[![My Skills](https://skillicons.dev/icons?i=js,html,css,java,mongodb)](https://skillicons.dev)

Software de gerenciamento de projetos internos 

O software a seguir tem o objetivo de auxiliar gerentes e equipes de projeto a organizar tarefas e responsabilidades. A interface e organizada em cards, com atribuição de responsáveis e informações relevantes sobre período de atuação, divisão de fases, entre outros. O gerente de projetos poderá utilizar o software para organizar projetos, atribuir tarefas aos respectivos usuários e gerenciar de prazo nas entregas de tarefa. Os usuários utilização a ferramenta de gestão de projetos para idealizar, planejar, administrar e celebrar o trabalho em conjunto de uma forma colaborativa. 

![WhatsApp Image 2023-05-07 at 15 01 30](https://user-images.githubusercontent.com/68711721/236701844-42ca6a0f-d415-4db2-8a3d-67aae19cc4a6.jpeg)

### Setup

Se desejar modificar o aplicativo ou hospedá-lo em seu próprio servidor, é possível clonar o repositório: 

git clone https://github.com/Gacarmo97/TCC-Pratica-Profissional-ADS.git

Para fazer este projeto foi utilizado as seguintes tecnologias:
Angular, Node JS, Docker com imagem de Mongo DB, Typescript e Socket IO, CSS.

Para conseguir rodar este projeto será necessário instalar:
- Um computador com sistema operacional Windows 10 64bits, mínimo de 600mb de espaço no dispositivo de armazenamento, processador Intel core i5 ou similar e memória RAM de 4GB+.

Para acessar o projeto baixe ou clone e abra o projeto no seu editor de código. 
Será preciso:
- Instalar NodeJS 18.16.0 LTS
https://nodejs.org/en

- Instalar Angular CLI com o comando: 
<npm install -g @angular/cli>
Para conferir se foi instalado utilize o comando:
*<ng version>*

- Para configurar o mongodb baixe e instale docker:
https://www.docker.com/
inicie seu Docker
No terminal do projeto execute o código:
<docker  run -d -p 27017-27019:27017-27019 --name mongodb mongo:4.0.4>
O resultado será esse:

![Docker_Mongo](https://github.com/Gacarmo97/TCC-Pratica-Profissional-ADS/assets/125417804/6030bf18-a39a-4732-a571-a31f4427a49a)

Rode o sotware localmente: 

Clicar com o botão direito na pasta CLIENTE e selecionar "open with integrated terminal"
comando: 
- "<npm install>"
- <npm start>

Clicar com o botão direito na pasta SERVER e selecionar "open with integrated terminal"
comandos: 
- <npm install ts-node -D>
- <npm start>

- Para acessar:
http://localhost:4200/

- No site para acessar os Boards basta fazer um cadastro clicando no botão Register, assim que terminar você estará logado.



