pipeline {
    agent {
        docker { image 'ubuntu' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'apt-get update'
		sh 'apt-get install git'
            }
        }
    }
}
