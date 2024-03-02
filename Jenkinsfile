pipeline {   
    agent any

    stages {   
        stage('development branch') { 
            steps { 
               sh 'echo "This is development new branch with webhook"' 
            }
        }
     
        stage('sprint1') { 
            steps { 
               sh 'echo "sprint1 application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
