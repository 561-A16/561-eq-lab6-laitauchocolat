FROM ymazieres/dotnet:compile

ENV ASPNETCORE_URLS http://+:5000

EXPOSE 5000

COPY /Docker/script.sh /script/script.sh
COPY /src/ /src/

RUN chmod +x /script/script.sh

CMD ["sh", "/script/script.sh"]
