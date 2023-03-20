node('built-in') 
{
    stage('master Continuous Download') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('master Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
}
