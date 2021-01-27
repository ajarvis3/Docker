# Gets runtime image
FROM mcr.microsoft.com/dotnet/aspnet:5.0

# Copy out directory to a directory called App in the container
COPY bin/out/net5.0/publish/ App/
# Set working directory inside the container
WORKDIR /App
# How to run as an executable, container stops when this command does
ENTRYPOINT ["dotnet", "NetCore.Docker.dll"]
