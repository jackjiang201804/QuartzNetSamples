FROM microsoft/aspnetcore:2.0

COPY bin/Release/PublishOutput  /app/

WORKDIR /app

ENTRYPOINT ["dotnet", "/app/App_NetCore.dll"]