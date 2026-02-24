pipeline {
    agent any

    stages {

        stage('Compile') {
            steps {
                bat 'python hello.py'
            }
        }

        stage('Run Program') {
            steps {
                bat 'python HelloWorld'
            }
        }
    }
}
