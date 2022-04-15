node('master') 
{
    stage('Continuous Download_2nd') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_2nd') 
	{
    sh label: '', script: 'mvn package'
	}
  
}
