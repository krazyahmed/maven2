node('master') 
{
    stage('Master-Download')
    {
       git 'https://github.com/selenium-saikrishna/maven2.git'
    }
    stage('Master-Build')
    {
       sh 'mvn package'
    }
    stage('Master-Deployment')
    {
        sh 'scp /home/vagrant/.jenkins/workspace/ScriptedPipeline/webapp/target/webapp.war vagrant@10.0.0.8:/var/lib/tomcat7/webapps/qaenv.war'
    
    
    

   
}
