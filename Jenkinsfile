node('built-in') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/vinothreddy/multibranchnew.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	
}
}
