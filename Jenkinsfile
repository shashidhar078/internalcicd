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
                    bat 'java -cp  src Hello.java'
                }
            }
        }
    
}