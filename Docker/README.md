# Container para API .NET

Eu preparei um Dockerfile multi-stage para compilar uma aplicação ASP.NET Core e executar a publicação em uma imagem menor.

A partir da pasta com um projeto .NET, use `docker build -t tarefas-api .`. Ajuste o caminho e o nome do arquivo `.csproj` antes de usar.
