FROM microsoft/aspnetcore:1.1
ARG source
RUN echo "source: $source"
WORKDIR /app
EXPOSE 80
COPY ${source:-/build} .
ENTRYPOINT ["dotnet", "webui.dll"]