pipeline{

    agent any

    stages{

        stage("compile"){
            steps{
                sh 'javac Test.java'
            }
        }
    }

    stages{

        stage("run"){
            steps{
                sh 'java Test'
            }
            
        }
    }
}