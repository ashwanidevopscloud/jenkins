pipeline {
    agent {
        label 'AGENT-1'
    }
        stages {
            stage("build") {
                steps {
                   
                    sh " echo this is build"
                    
                }
            }
              stage("Test") {
                steps {
                 
                    sh "echo this is test"
                   
                }
            }
              stage("deploy") {
                steps {
                   
                    sh "echo this is deploy"
                    
                }
            }
        }

        post { 
        always { 
            echo 'I will always say Hello again!'
        }
        failure {
            echo ' i will be failure'
        }
        success {
            echo 'It will be success'
        }
    }
    
}