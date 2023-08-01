# Comandos
- sobe o docker no modo dinamo -> docker-compose up -d
- lista os serviços do docker - docker-compose ps
- Verificar os banco de dados -> docker-compose exec db psql -U postgres -c '\l'
- para os serviços do docker e rede -> docker-compose down
- Lista banco e tabelas -> sudo docker-compose exec db psql -U postgres -f /scripts/check.sql
