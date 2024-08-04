pipeline{
    agent {
        label "AGENT-1"
    }
    options{
        timeout(time: 20, unit: 'MINUTES')
         disableConcurrentBuilds()

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
                sh 'sleep 23'
            }
        }
        stage("Doply"){
            steps{
                sh "echo This Doply"
            }
    

    }
}}