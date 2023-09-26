node('built-in') 
{
    stage('Continuous Download_loans') 
	{
    git 'https://github.com/AdmVishal/repo_multi26092023.git'
	}
    stage('Continuous Build_loans') 
	{
    sh label: '', script: 'mvn package'
	}
}
