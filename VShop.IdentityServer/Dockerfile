FROM mcr.microsoft.com/dotnet/aspnet:6.0
LABEL version="1.0.1" description="Microsservico IdentityServer"
COPY dist /app
WORKDIR /app
EXPOSE 80/tcp
ENTRYPOINT ["dotnet","VShop.IdentityServer.dll"]