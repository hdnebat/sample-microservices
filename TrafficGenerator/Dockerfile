FROM microsoft/dotnet:2.2.1-aspnetcore-runtime-alpine
WORKDIR /app
COPY traffic-gen/ /app/
ARG ELK_URLS
ARG CUSTOMER_SERVICE_URL
ARG JAEGER_SERVICE_NAME
ARG JAEGER_AGENT_HOST
ARG JAEGER_AGENT_PORT
CMD ["dotnet", "TrafficGenerator.dll"]