pipeline {
     agent any {
          label 'local'
     }
    options {
        // Timeout counter starts AFTER agent is allocated
        timeout(time: 5, unit: 'SECONDS')
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
