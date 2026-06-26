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
    alwasys {
        echo 'Pipeline is Success'
    }
    success {
        echo 'okay'
    }
}
}