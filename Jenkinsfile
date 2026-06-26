pipeline{
    agent none
    options {
        timeout (time: 10, unit: 'SECONDS')
    }
    //Build
    stages{
        stage('Build'){
            steps{
                echo 'Building'
                sleep 10
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