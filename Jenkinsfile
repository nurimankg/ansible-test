// Jenkinsfile (Declarative Pipeline)
pipeline {
   agent { node { label 'mysql_node' }
   }

   stages {
     stage("pwd"){
       steps{
        sh "pwd"
       }
     }
     
     stage("whoami"){
       steps{
        sh "whoami"
       }
     }
   }     
} 
