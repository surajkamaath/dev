pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                git url: 'https://github.com/surajkamaath/Internals1', branch: 'main'
            }
        }

        stage('Run Script') {
            steps {
                sh 'chmod +x script.sh'
                sh './script.sh'
            }
        }

    }
}
