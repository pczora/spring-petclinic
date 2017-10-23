pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh './mvnw --batch-mode -V -U -e clean install'
            }
        }
    }
}
