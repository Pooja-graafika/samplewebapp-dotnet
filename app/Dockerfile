FROM mcr.microsoft.com/dotnet/aspnet:5.0
WORKDIR /WebApp
COPY drop/app/SampleWebApp/bin/Debug/net6.0/SampleWebApp.dll ./
ENTRYPOINT ["dotnet", "SampleWebApp.dll"]
