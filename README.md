# GoBarber

- Docker:
  Criar container:
  docker run --name database -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres
  Parar:
  docker stop database
  Listar:
  docker ps || docker ps -a
  Iniciar: docker start database
  Erros: docker logs database
