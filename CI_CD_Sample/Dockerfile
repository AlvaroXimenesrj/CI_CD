FROM mcr.microsoft.com/dotnet/core/aspnet:5.0
COPY dist /app
WORKDIR /app
EXPOSE 80
ENTRYPOINT ["dotnet", "CI_CD_Sample.dll"]