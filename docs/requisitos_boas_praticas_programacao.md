# Requisitos de boas praticas de programação

## Geral
-	Todas os commits devem ser feitos no padrao de:
		{tipo}: {descricao}
	Em que o tipo pode ser:
		-	Feat -> funcionalidades
		-	Fix -> ajuste de bugs
		-	refactor -> refatoração de codigo
		-	docs -> ajuste na documentação
		-	test -> modificações em testes unitarios
		-	ci -> modificação em etapas de CI/CD
		-	build -> modificações em dependencias externas do projeto
-	Apos um commit todos os testes unitarios devem ser executados automaticamente e em caso de erro nao permitir o commit
-	Apos um commit deve ser verificado se a mensagem segue o padrao

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