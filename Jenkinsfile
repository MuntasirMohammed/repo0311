node('built-in') 
{
    stage('Continuous Download_loans') 
	{
    git 'https://github.com/yankils/hello-world.git'
	}
    stage('Continuous Build_loans') 
	{
    sh label: '', script: 'mvn package'
	}
    
}
