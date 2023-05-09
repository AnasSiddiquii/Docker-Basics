FROM openjdk

WORKDIR /usr/src/myapp

COPY . /usr/src/myapp/

RUN javac Hello.java

CMD ["java", "Hellop"]

# ! Terminal Command
# docker build -t javaimage . 
# docker run --name javacontainer javaimage