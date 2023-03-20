node('built-in') 
{
    stage('Training Continuous Download') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Training Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
    stage('Training Continuous deploy')
	{
    sh 'scp /home/ec2-user/.jenkins/workspace/development/webapp/target/webapp.war ec2-user@172.31.31.174:/var/lib/tomcat/webapps/testenv.war'
    	}
}
