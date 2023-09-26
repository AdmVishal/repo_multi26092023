node('built-in') 
{
    stage('Continuous Download_Master') 
	{
    git 'https://github.com/AdmVishal/repo_multi26092023.git'
	}
    stage('Continuous Build_Master') 
	{
    sh label: '', script: 'mvn package'
	}
}
