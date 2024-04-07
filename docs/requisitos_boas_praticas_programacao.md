# Requisitos de boas praticas de programação

## Front-end

-	Uso de tokens do temas, para facilitar uma possivel mudança de um tema
-	Uso do server-side para garantir uma melhor performance da aplicação
-	Criação de componentes reutilizaveis
-	Utilização da arquitetura app router do NextJs
-	Para componentes reutilizaveis utilizar o atomic design (atoms, molecules, organisms) 

## Back-end
- Uso da arquitetura controller -> useCase -> repository
- Uso do typeorm
	- Evitar utilizar queries raw e preferir utilizar o EntityManager ou QueryBuilder
	- Estruturação das entidades de forma clara e bem estruturada
	- Utilização de migrations para criação e modificação da base
- Criação de logs claro na aplicação para facilitar o monitoramento
- Documentar as rotas no swagger