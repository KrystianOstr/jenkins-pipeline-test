pipeline {
    agent any 

    environment {
        AUTHOR = "Krystian - github"
    }

    stages {
        stage('Start') {
            steps {
                echo "uruchomiono z repo: ${AUTHOR}"
                sh 'date'
            }
        }
        
        stage('Build') {
            steps {
                echo "test webhooook"
            }
        }
    }

    post {
        success {
            echo    "DONE"
        }
        failure {
          echo  "ERROR!"
        }
    }
}