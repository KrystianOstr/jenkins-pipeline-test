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
                echo "sh buduje z repo"
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