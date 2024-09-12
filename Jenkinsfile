pipeline{
    agent{
        label 'A-1'
    }
    options {
        // Timeout counter starts AFTER agent is allocated
        timeout(time: 1, unit: 'SECONDS')
    }

    stages{
        stage("Build"){
            steps{
                sh 'echo Build'
                sleep(1000)
            }
        }
    stage("Test"){
            steps{
                sh 'echo Test'
            }
        }

        stage("depoly"){
        steps{
            sh 'echo depoly'
        }

    }
}}