pipeline {
    agent any
    stages {
      stage('Stage 1') {
            steps {
               sh """
                   echo "Executing stage1" 
                   
               """
            }
        }
        stage('Init') {
             steps {
                sh """
                   cd terraform
                   terraform init -reconfigure  
                """
            }
        }  
  }
}
