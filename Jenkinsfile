pipeline{

    agent any
    environment {
        APP_ENV = "staging"

    }
    options{
        timeout(time: 2, unit: 'SECONDS')
    }
        stages{
            stage('Hello'){
                steps {
                sleep time: 15, unit: 'SECONDS'
                echo "build number: ${env.BUILD_NUMBER}"
                echo 'Hello World'
                echo "${APP_ENV}"
            }
                
            stage("stage number one"){
                steps{
                    echo "Avital & Rachely"
                }

            }
            stage('build'){
                steps {
                echo 'The second stage'
                echo "The second step"
            }

        }


}
   



