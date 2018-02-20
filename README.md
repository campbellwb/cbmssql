# Mssql

A docker-compose which will build a Microsoft Sql Server container for quick deployment.

Configure the password in /.env

## Getting Started

Make sure you have docker installed.

Platforms: Linux, OSX and Windows.

### Prerequisites

See above.

### Installing

* Set the password in /.env
* docker-compose up
* Once docker finishes initalising the container, there will be a Sql Server instance running at localhost:1433

## Built With

* [Docker](https://www.docker.com/) - Containerisation platform
* [Microsoft Sql Server image for linux](https://hub.docker.com/r/microsoft/mssql-server-linux/) - Official image for Microsoft Sql Server for Linux

## Authors

* **Campbell Bartlett**

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Change log

* 1.0 Initial Commit