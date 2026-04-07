pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo "Cloning done"
            }
        }

        stage('Run Code') {
            steps {
                echo "Running Python file"
                sh 'python3 app.py'
            }
        }
    }
}
