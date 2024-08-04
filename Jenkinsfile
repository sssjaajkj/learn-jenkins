pipeline{
    agent {
        label "AGENT-2"
    } 
    stages{}
    stage("Build"){

        steps{
        sh 'echo this Build'
        }
    }

    stage("Test"){
        steps{
            sh 'echo this Test'
        }
    }

       stage("Depoly")
       steps{
        sh 'echo this Depoly'
       } 

}