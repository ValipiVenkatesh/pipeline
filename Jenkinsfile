pipeline {
    agent any
    stages{
        stage('Git-Checkout'){
            steps{
                echo "Checkout out from Git Repo"
                git branch: 'main', url: 'https://github.com/ValipiVenkatesh/pipeline.git'
                
            }
        }
        stage('Test'){
            steps{
                echo "Testing completed"
            }
        }
        
    }
}
