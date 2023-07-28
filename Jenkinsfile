pipeline {
    agent any

    stages {
        stage('Deploy Magento') {
            steps {
                echo 'Deploying and cleaning'
                sh 'echo $(date +%s) > ~/jenkins_build_test.log'
            }
        }
    }

    post {
        always {
            cleanWs()
        }
    }
}
