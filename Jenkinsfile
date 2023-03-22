node('built-in') 
{
    stage('learning Continuous Download') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('learning Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
    stage('learning Continuous test')
        {
    sh 'echo "Testing Completed"'
        }
}
