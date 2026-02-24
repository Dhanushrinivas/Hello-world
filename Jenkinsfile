pipeline {
    agent any

    stages {

        stage('Compile') {
            steps {
                bat 'javac HelloWorld.java'
            }
        }

        stage('Run Program') {
            steps {
                bat 'java HelloWorld'
            }
        }
    }
}
