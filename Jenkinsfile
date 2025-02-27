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
sh ' export MAVEN_HOME=/opt/apache-maven-3.9.5 && export PATH=$PATH:/opt/apache-maven-3.9.5/bin && mvn -f /var/lib/jenkins/workspace/abcd4/javawar/pom.xml install && rm -rf javawar'
}
}
}
}
