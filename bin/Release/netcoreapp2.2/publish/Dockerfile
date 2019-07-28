FROM gcr.io/google-appengine/aspnetcore:2.1
COPY . /app
WORKDIR /app
ENV ASPNETCORE_URLS=http://*:${PORT}
ENTRYPOINT ["dotnet", "ContosoUniversity.dll"]
