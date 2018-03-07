node('maven') 
{
	stage 'build'
		echo 'building application'
	stage 'deploy'	
		echo 'deploying application'
		sh 'ls -la'
		sh 'mvn package'
}