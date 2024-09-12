pipeline{
    agent{
        label 'A-1'
    }
    options {
        // Timeout counter starts AFTER agent is allocated
        timeout(time: 20, unit: 'SECONDS')
         disableConcurrentBuilds()
    }

    //  parameters {
    //     string(name: 'PERSON', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')

    //     text(name: 'BIOGRAPHY', defaultValue: '', description: 'Enter some information about the person')

    //     booleanParam(name: 'TOGGLE', defaultValue: true, description: 'Toggle this value')

    //     choice(name: 'CHOICE', choices: ['One', 'Two', 'Three'], description: 'Pick something')

    //     password(name: 'PASSWORD', defaultValue: 'SECRET', description: 'Enter a password')
    // }

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