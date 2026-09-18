pipeline{
    agent any
        stages{
            stage('Build'){
                steps{
                    bat 'javac src/Hello.java'
                }
            }
            stage('Run'){
                steps{
                    bat 'javac -cp  src src/Hello.java'
                }
            }
        }
    
}