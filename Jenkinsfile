pipeline{
    agent none
    options {
        timeout (time: 10, unit: 'SECONDS')
    environment {
        course: 'Devops'
    }    
    }
    //Build
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