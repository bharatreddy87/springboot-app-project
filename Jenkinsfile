pipeline {
    agent any
    stages {
         stage('Task Main1') {
                    steps {
                        sh 'echo "Define steps for Task main"'
                    }
                }
        stage('Parallel Stage') {
            parallel {
                stage('Task 1') {
                    steps {
                        sh 'echo "Define steps for Task 1"'
                    }
                }
                stage('Task 2') {
                    steps {
                        sh 'echo "Define steps for Task 2"'
                    }
                }
            }
        }
    }
}
