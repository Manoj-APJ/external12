pipeline {
    agent any
    stages {
        stage('git hub access') {
            steps {
                git url: 'https://github.com/Manoj-APJ/sample3'
            }
        }
        stage('Java code execution') {
            steps {
                script {
                    bat 'javac Helloworld.java && java Helloworld'
                }
            }
        }
        stage('python code execution') {
            steps {
                script {
                    bat 'python helloworld.py'
                }
            }
        }
    }
}
