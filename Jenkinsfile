node('built-in') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/vinothreddy/newmulti.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	
}
}
