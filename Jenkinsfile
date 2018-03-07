node('maven') 
{
	git url: 'git@github.com:hhtay-paloit/clusterapp.git'

	stage 'build'
		echo 'building application'
	stage 'deploy'	
		echo 'deploying application'
		sh 'ls -la'
		sh 'mvn package'
}