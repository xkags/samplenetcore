pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'docker build -t lastone -f DockerFile .'
                sh 'docker push ozzie/lastone'
             //   sh 'docker run -d -p 10080:80 lastone'
            }
        }
    }
}
