# Requisitos de boas praticas de segurança

- Autenticação utilizando bearer token (JWT)
- Armazenar o token nos cookies com as flags HTTPOnly e Secure
- Armazenar credenciais do usuario via hash no banco de dados
- Controle dos consumos das requisições para que apenas recursos do mesmo dominio sejam consumidos
- Utilização de um key vault para armazenar as variaveis de ambientes
- Não permitir o push de variaveis sensiveis, como chaves de acesso