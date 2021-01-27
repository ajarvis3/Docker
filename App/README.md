# Build Docker Container with .NET

Following Tutorial to build a Docker container with
.NET project

Based on https://docs.microsoft.com/en-us/dotnet/core/docker/build-container?tabs=windows
but use .NET 5.0 instead of .NET Core 3.1

Build Docker image with `docker build -t counter-image -f Dockerfile .`

Create container with `docker create --name core-counter counter-image`

Start with `docker start core-counter`

View output with `docker attach --sig-proxy=false core-counter`
Close with `Ctrl+C`

Stop with `docker stop core-counter`