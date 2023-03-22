FROM tomcat:8.0.36-alpine
# Author.
MAINTAINER jj_bond
# Add war.
ADD easy-springmvc-maven.war /usr/local/tomcat/webapps/
# Define working directory.
WORKDIR /usr/local/tomcat/bin/
# Define environment variables.
ENV PATH /usr/local/tomcat/bin:$PATH
# Define default command. 
CMD ["catalina.sh", "run"]
# Expose ports.
EXPOSE 8080