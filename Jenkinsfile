pipeline{
    agent any 
    stages{
        stage('1-clone code or build'){
            steps{
                checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: '6a94cd96-5180-492d-b3ff-1f7d6d9a98f9', url: 'https://github.com/etech-team5group2/TeetoAppBank.git']])
                }
         }
         stage('2-memorycheck'){
            steps{
                sh 'free -g'
      
            }
         }
         stage('3-welcomepage'){
            steps{
                echo "Welcome to Jenkins Module"
            }
        }
        
    }
}
