pipeline {
    agent any

    stages {
        stage('Checking python version') {
            steps {
                bat 'python -v'
            }
        }
        stage('Cloning repository') {
            steps {
                bat 'copy /S "*" " C:/Xamp/htdocs/exp4" /Y'
            }
        }
        stage('printing done') {
            steps {
                echo 'Done'
            }
        }
    }
}
