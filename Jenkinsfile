node('master') 
{
    stage('Continuous Download_1st') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_1st') 
	{
    sh label: '', script: 'mvn package'
	}
  
}
