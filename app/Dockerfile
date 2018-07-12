FROM microsoft/dotnet:2.1-aspnetcore-runtime

WORKDIR /app
COPY bin/Debug/netcoreapp2.1/publish .

ENV ASPNETCORE_URLS http://+:5000
EXPOSE 5000

ENTRYPOINT [ "dotnet", "app.dll" ]