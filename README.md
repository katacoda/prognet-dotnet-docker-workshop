# Katacoda - Running .NET inside Docker workshop

Katacoda Course: https://www.katacoda.com/courses/dotnet-in-docker/

Katacoda is an interactive learning platform for software developers hosting pre-build environments and labs. The Katacoda course on "Running DotNet on Docker" provides you with an Docker environment with the required images and sample source code.

If you'd prefer not to use the free Docker environment in your browser with Katacoda then it's recommended to use Digital Ocean or Docker Toolbox

## Digital Ocean Droplet

$10 Digital Ocean Credit via https://m.do.co/c/dd50443ebb28

Launch Ubuntu with Docker, no need for Windows in this workshop.

Please remember to stop the droplet at the end of the workshop.

## Running Locally with Docker Toolbox

If you prefer to run the workshop locally, install Docker from https://www.docker.com/getdocker

### Docker Images

This will download all the base images used by the examples.

```
docker pull ocelotuproar/docker-alpine-mono:4.4
docker pull microsoft/dotnet:1.0.0-preview1
docker pull microsoft/dotnet:1.0.0-preview1-onbuild
docker pull ocelotuproar/docker-alpine-fsharp:4.0
docker pull ocelotuproar/docker-alpine-scriptcs:0.16.1
docker pull ocelotuproar/alpine-node:5.7.1
```

### Examples

This is a collection of example Hello World web applications designed to help you understand running DotNet applications inside containers.

```
git clone https://github.com/katacoda/dotnet-nancy-nuget-example
git clone https://github.com/katacoda/dotnet-aspnet-core-example
git clone https://github.com/katacoda/dotnet-fsharp-example
git clone https://github.com/katacoda/dotnet-scriptcs-example
git clone https://github.com/katacoda/nodejs-express-example
```
