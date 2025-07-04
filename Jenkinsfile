pipeline{

    agent any

    stages{

        stage("compile"){
            sh 'javac Test.java'
        }
    }

    stages{

        stage("run"){
            sh 'java Test'
        }
    }
}