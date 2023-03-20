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
}
