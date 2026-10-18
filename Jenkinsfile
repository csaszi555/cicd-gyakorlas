pipeline {
    agent any

    stages {
        stage('Cim ellenorzese') {
            steps {
                sh 'grep -q "<title>" index.html'
            }
        }
        stage('HTML ellenorzese') {
            steps {
                sh 'echo "Itt futna a tidy ellenorzes"'
            }
        }
    }
}