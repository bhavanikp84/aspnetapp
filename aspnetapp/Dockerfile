FROM mcr.microsoft.com/dotnet/aspnet:8.0-alpine AS base

WORKDIR /app
EXPOSE 5001
EXPOSE 5003

# Copy files from the artifact staging folder on agent
COPY /out .
ENTRYPOINT ["dotnet", "aspnetapp.dll"]
