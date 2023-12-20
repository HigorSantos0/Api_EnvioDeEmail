# Conceito

O projeto basicamente tem o intuito de fazer um envio da mensagem 
especificamente por email, usando alguns conceitos do Spring Boot.

# Uso

Java 21,
Spring Boot,
mailTrap

#  Como testar?

1°: Criar uma conta do emailTrap
2°: Por suas credenciais que foram criadas automaticamente no properties do projeto
3°: Run no projeto
4°: execute esse comando no GitBash, ou no terminal de sua preferência(Comando pode ser diferente).
    Java```
     curl -X POST http://localhost:8080/email -H "Content-Type: application/json" -d '{"to": "higor@email.com", "subject": "demo Spring mail", "body": "teste email"}' -v
    ```
