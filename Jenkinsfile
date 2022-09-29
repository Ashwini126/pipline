pipeline {  
    agent any  
    stages {  
            stage ('Build') {  
                steps {  
                        echo 'Running build phase...'  
                }  
            }  
            stage('Test') {
               steps {
                    echo 'Testing..'
               }
            }
           stage('Deploy') {
                steps {
                     echo 'Deploying....'
                }
            }
          stage ('Monitor') { 
            steps {
                     echo 'Monitoring....'
                }
          }
    }  
}  
