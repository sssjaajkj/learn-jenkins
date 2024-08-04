pipeline{
    agent {
        label "AGENT-1"
    }
    options{
        timeout(time: 11, unit: 'MINUTES')
         disableConcurrentBuilds()
    }
parameters {
        string(name: 'PERSON', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')

        text(name: 'BIOGRAPHY', defaultValue: '', description: 'Enter some information about the person')

        booleanParam(name: 'TOGGLE', defaultValue: true, description: 'Toggle this value')

        choice(name: 'CHOICE', choices: ['One', 'Two', 'Three'], description: 'Pick something')

        password(name: 'PASSWORD', defaultValue: 'SECRET', description: 'Enter a password')
    }

    environment{
        DEPLOY_TO = "production"
        GREETING = "Good Morning"
    }
    stages{
        stage("Build"){
            steps{
                sh "echo This Bild"
                sh 'env'
               
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

     stage('Example') {
            steps {
                echo "Hello ${params.PERSON}"

                echo "Biography: ${params.BIOGRAPHY}"

                echo "Toggle: ${params.TOGGLE}"

                echo "Choice: ${params.CHOICE}"

                echo "Password: ${params.PASSWORD}"

                error "Issues"
            }}
    }


post { 
        always { 
            echo 'I will always say Hello again!'
        }

        success { 
            echo 'I will success say Hello again!'
        }

        failure { 
            echo 'I will failured say Hello again!'
        }
    }



}
