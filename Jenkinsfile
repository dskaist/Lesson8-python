pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                git 'https://github.com/dskaist/Lesson8-python.git'
                bat 'python ./lesson8-python-pipeline/main.py'
            }
        }
    }
}
