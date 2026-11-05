
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Test') {
            steps {
                bat '"C:/Users/Shanks/AppData/Local/Programs/Python/Python314/python.exe" -m unittest -v'
            }
        }
    }
}
