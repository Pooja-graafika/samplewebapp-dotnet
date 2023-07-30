FROM mcr.microsoft.com/dotnet/aspnet:5.0
WORKDIR /WebApp
COPY --from=build *.dll ./
ENTRYPOINT ["dotnet", "SampleWebApp.dll"]
