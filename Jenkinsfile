

node('maven') 
{
	git url: 'git@github.com:hhtay-paloit/clusterapp.git', credentialsId: "tayhh-mvn-private-git"

	stage 'build'
		echo 'building application'
	stage 'deploy'	
		echo 'deploying application'
		sh 'ls -la'
		sh 'mvn package'
}