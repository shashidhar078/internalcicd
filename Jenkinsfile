pipeline{
    agent any
        stages{
            stage('Build'){
                steps{
                    bat 'javac src/Hello.java'
                }
            }
            stage('run'){
                steps{
                    bat 'javac -cp  src Hello.java'
                }
            }
        }
    
}