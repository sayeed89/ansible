pipeline {
    agent any

    stages {
        stage('BUILD') {
            steps {
                sh 'ansible-lint clear.yml'
            }
        }
    }
}
