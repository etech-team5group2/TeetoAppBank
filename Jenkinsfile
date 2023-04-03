pipeline{
    agent any 
    stages{
        stage('1-clone code or build'){
            steps{
                sh 'du -h'
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
