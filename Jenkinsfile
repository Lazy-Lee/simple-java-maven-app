pipeline {
    agent {
        docker {
            image 'maven:latest' 
            args '-v /Users/liqingxian/.m2:/root/.m2' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
