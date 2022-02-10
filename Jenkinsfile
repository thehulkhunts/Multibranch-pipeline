pipeline {
agent any 
    stages{
        stage('get scm clone'){
        steps {
         sh 'echo " cloning source code management" '
         }
        }
         stage('building maven packages'){
         steps{
          sh 'echo "building war files " '
          }
         }
         
         stage('deploying into server'){
         steps{
         sh 'echo " deploying into production" '
         }
         }
    }
       
        
}

