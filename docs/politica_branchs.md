# Politica de branchs

Branch main com o codigo testado e que representa o codigo que vai estar disponivel no ambiente de producao;
Branch dev com o codigo ainda em desenvolvimento e que será utilizado para testes;
branch feat/descricao (feature branch) Criada a partir de dev vai conter o codigo apenas da funcionalidade especifica;
Branch hotfix/descricao (hotfix) Criada a partir de main e vai conter o codigo da correção de um bug que precisa ser resolvido rapidamente;

## Pull Requests

Feature branch -> dev 
Nesses Pull request irá direcionar o codigo da funcionalidade para a branch de dev

dev -> main
Release das funcionalidades ja testada

hotfix -> main e hotfix -> dev
A branch de hotfix deve ir tanto para dev quanto para main para que os codigos se mantenham iguais