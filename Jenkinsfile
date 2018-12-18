node('master') 
{
    stage('Feature-1-Download')
    {
       git 'https://github.com/selenium-saikrishna/maven2.git'
    }
    stage('Feature-1-Build')
    {
       sh 'mvn package'
    }
    stage('Feature-1-Deployment')
    {
        sh 'scp /home/vagrant/.jenkins/workspace/MultibranchPipleine/webapp/target/webapp.war vagrant@10.0.0.8:/var/lib/tomcat7/webapps/feature1.war'
    }
    
    
    
    
    

   
}
