pipeline {
    agent any

    stages {
        stage('Deploy Magento') {
            steps {
                echo 'Deploying and cleaning'
                sh 'echo $(date +%s)'
            }
        }
    }

    post {
        always {
            cleanWs()
        }
    }
}
