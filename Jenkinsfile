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
    successs {
        echo 'okay'
    }
    failure {
        echo 'failure'
    }
}
}