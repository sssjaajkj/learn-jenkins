pipeline{
    agent {
        label 'A-12'
    }
        stages{
            stage("Build") {
                steps{
                   sh 'echo This is Build ' 
                }
              }

           stage ('Test'){
            steps{
                sh 'echo This is Test'
            }
            }

            stage("Depoly"){
                steps{
                    sh 'echo Ths is Depoly'
                }
            }   
    }
}