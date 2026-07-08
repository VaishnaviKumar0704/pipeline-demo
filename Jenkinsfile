pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello Jenkins!'
            }
        }

        stage('Run Linux Command') {
            steps {
                sh 'pwd'
                sh 'ls -l'
            }
        }
    }
}
