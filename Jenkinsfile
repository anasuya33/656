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
sh 'mvn -f /var/lib/jenkins/workspace/656/javawar/pom.xml install'
}
}
}
}
