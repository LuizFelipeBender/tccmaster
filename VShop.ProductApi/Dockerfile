FROM mcr.microsoft.com/dotnet/aspnet:6.0
LABEL version="1.0.1" description="Microsservico VShop.ProductApi"
COPY dist /app
WORKDIR /app
EXPOSE 80/tcp
ENTRYPOINT ["dotnet","VShop.ProductApi.dll"]