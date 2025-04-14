pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                echo 'Cloning the repository... Already done by Jenkins'
            }
        }

        stage('Run Script') {
            steps {
                echo 'Running the hello script...'
                sh 'chmod +x hello.sh && ./hello.sh'
            }
        }
    }
}
