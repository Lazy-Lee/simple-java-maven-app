pipeline{
	agent{
		docker{
			image 'maven:latest
			args '-v /root/.m2
}
}
	stages{
		stage('Build'){
			steps{
				sh 'man -B -DskipTests clean package'
}
}
}
}
