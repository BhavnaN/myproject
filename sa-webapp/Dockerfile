FROM openjdk:8-jdk-alpine
# Environment Variable that defines the endpoint of sentiment-analysis python api.
ENV SA_LOGIC_API_URL http://localhost:5000
ENV WEBAPP_SERVER_PORT 8181
ADD target/sentiment-analysis-web-0.0.1-SNAPSHOT.jar /
EXPOSE 8181
CMD ["java", "-jar", "sentiment-analysis-web-0.0.1-SNAPSHOT.jar", "--sa.logic.api.url=${SA_LOGIC_API_URL}", "--server.port=${WEBAPP_SERVER_PORT}"]
