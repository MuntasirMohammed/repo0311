node('built-in') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/yankils/hello-world.git'
	}
    stage('Continuous Build_master') 
	{
    sh label: '', script: 'mvn package'
	}
    
}
