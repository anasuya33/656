pipeline 
{

agent any

stages

{
stage ('1')

{
steps
{
sh ' git clone https://github.com/RavitejaAdepudi/javawar.git'
}
}
  stage ('2')

{
steps
{
sh ' export MAVEN_HOME=/opt/apache-maven-3.9.5 && export PATH=$PATH:/opt/apache-maven-3.9.5/bin && mvn -f /var/lib/jenkins/workspace/abcd4/javawar/pom.xml install '
}
}
  stage ('3')

{
steps
{
sh ' cp -R  /var/lib/jenkins/workspace/abcd4/javawar/target/*.war /opt//opt/apache-tomcat-9.0.99/webapps '
}
}
}
