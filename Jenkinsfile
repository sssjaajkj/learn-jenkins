pipeline{
    agent {
        label 'A-12'
    }

    options{
        timeout(time: 1, unit: 'SECONDS')
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
                sh 'sleep 10'
            }
            }

            stage("Depoly"){
                steps{
                    sh 'echo Ths is Depoly'
                }
            }   
    }
}