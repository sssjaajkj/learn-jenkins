pipeline{

    agent any
        stages{
            stage{
                steps("Build"){

                sh 'This is Build ' 
                }
              }

           stage{
            steps('Test'){
                sh 'This is Test'
            }
            }

            stage{
                steps("Depoly"){
                    sh 'Ths is Depoly'
                }
            }   
    }
}