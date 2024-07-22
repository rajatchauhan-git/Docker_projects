# base image
FROM openjdk:17-jdk-alpine

# working dir
WORKDIR /app

# copy code into container
COPY src/Main.java /app/Main.java

# Compile code
RUN javac Main.java

# Run
CMD ["java","Main"]
