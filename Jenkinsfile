pipeline{
    agent {
        label "AGENT-1"
    }
    options{
        timeout(time: 1, unit: 'SECONDS')
    }
    stages{
        stage("Build"){
            steps{
                sh "echo This Bild"
               
            }
        }
        stage("Test"){
            steps{
                sh "echo This Test"
                sh 'sleep 10'
            }
        }
        stage("Doply"){
            steps{
                sh "echo This Doply"
            }
    

    }
}}