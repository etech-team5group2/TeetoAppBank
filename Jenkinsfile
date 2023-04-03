pipeline{
    agent any 
    stages{
        stage('1-clone code or build'){
            steps{
                sh 'du -h'
                sh'os-release'
                }
         }
         stage('2-memorycheck'){
            steps{
                sh 'free -g'
                sh 'cat etc/os-release'
            }
         }
         stage('3-welcomepage'){
            steps{
                echo "Welcome to Jenkins Module"
            }
        }
        
    }
}