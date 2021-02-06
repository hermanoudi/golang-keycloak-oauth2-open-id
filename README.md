# golang-keycloak-oauth2-open-id
Projeto em Golang de testes que mostra uma forma de autenticação e autorização utilizando o keycloak e openid-connect.
Keycloak utilizado local com docker conforme a documentação do keycloak.
https://www.keycloak.org/

docker run -it -p 8080:8080 -e KEYCLOAK_USER=admin -e KEYCLOAK_PASSWORD=admin -e DB_VENDOR=h2 quay.io/keycloak/keycloak:12.0.2
