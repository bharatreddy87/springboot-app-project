pipeline {
    agent any
    stages {
        stage('Parallel Stage') {
            parallel {
                stage('Task 1') {
                    steps {
                        // Define steps for Task 1
                        sh 'touch bharath.txt'
                    }
                }
                stage('Task 2') {
                    steps {
                        // Define steps for Task 2
                        sh 'mkdir bharath{1..10}'
                    }
                }
            }
        }
    }
}
