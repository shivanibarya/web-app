pipeline {
    agent any

    stages {
        stage('Code') {
            steps {
              git 'https://github.com/ramyachetty/web-app.git'
            }
        }
        stage('code-build') {
            steps {
                 sh "mvn clean package"
            }
        }
    }
}
