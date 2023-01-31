# Video Sharing Platform

This is a video sharing platform that allows users to upload videos and share them with other users. The platform also provides a Swagger UI to test the API.

Created as part of the [Alura Challenge](https://www.alura.com.br/challenges/back-end) 2021. :rocket:

## Getting Started

### Prerequisites

Install the Docker Desktop from [here](https://www.docker.com/products/docker-desktop)

## How to run

In the project's root folder, run the following command to set the connection string for the PostgreSQL database:
```
docker-compose up -d
```

## How to use

The video sharing service provides a Swagger UI to test the API. You can access it by navigating to the following URL: http://localhost:5000/swagger/index.html.

The identity service provides a Swagger UI to test the API. You can access it by navigating to the following URL: http://localhost:5001/swagger/index.html.

## Built With

- [Docker](https://www.docker.com/) - Containerization
- [ASP.NET Core](https://dotnet.microsoft.com/apps/aspnet) - Web framework
- [Entity Framework Core](https://docs.microsoft.com/en-us/ef/core/) - ORM
- [JWT](https://jwt.io/) - Authentication
- [Swagger](https://swagger.io/) - API documentation
- [xUnit](https://xunit.net/) - Unit testing framework

## Architecture

The platform is composed of 2 services:

- **Video Sharing Service**: this service is responsible for managing videos. It exposes a REST API that can be used to upload videos and share them with other users. The service also provides a Swagger UI to test the API. You can find the service's project [here](https://www.github.com/brunoaragao/video-sharing-platform-video-sharing-service).

- **Identity Service**: this service is responsible for managing user authentication. It exposes a REST API that can be used to authenticate users and generate JWT tokens. The service also provides a Swagger UI to test the API. You can find the service's project [here](https://www.github.com/brunoaragao/video-sharing-platform-identity-service).

## Acknowledgments

- [Alura](https://www.alura.com.br/)

## Authors

- **[Bruno Aragão](https://github.com/brunoaragao)**

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.