Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker 'node:12.14.0' }
    stages {
        stage('build') {
            steps {
                sh 'echo "hello jenkins"'
                sh '''
                    echo "Multiline shell steps works too"
                '''
            }
        }
    }
}
