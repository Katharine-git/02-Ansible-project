pipeline{
    agent any

    stages{
        stage('Compile stage'){

            steps{
                withMaven('maven'){
                    sh 'mvn clean compile'
                }
            }
        }
    
    stage('Testing stage'){

            steps{
                withMaven('maven'){
                    sh 'mvn test'
                }
            }
        }
    stage('Testing stage'){

            steps{
                withMaven('maven'){
                    sh 'mvn test'
                }
            }
        }
    
    stage('Testing deploy'){

            steps{
                withMaven('maven'){
                    sh 'mvn deploy'
                }
            }
        }
}   }