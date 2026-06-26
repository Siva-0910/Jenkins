pipeline{
    agent none
    stages{
        stage('Build'){
            steps{
                echo 'Building'
            }
        }
    }
post{
    always {
        echo 'Pipeline is Success'
    }
    success {
        echo 'okay'
    }
    failure {
        echo 'failure'
    }
}
}