pipeline {
    agent {
        docker {
            image 'myjenkins-blueocean:2.414.3-1'
            args '-p 3000:3000'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
    }
}
