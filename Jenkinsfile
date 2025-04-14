pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                echo 'Cloning the repository...'
                git 'https://github.com/AbinMathew16/jenkins-hello-world.git'
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
