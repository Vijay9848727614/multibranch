pipeline {   
    agent any

    stages {   
        stage('Develoment  branch') { 
            steps { 
               sh 'echo "This is Development branch"' 
            }
        }
     
        stage('sprint1') { 
            steps { 
               sh 'echo "Development application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
