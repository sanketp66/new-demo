# new-demo
#sample-code-1

pipeline {
    agent any
    stages {
        stage('Welcome') {
            steps {
                echo 'Welcome'
            }
        }
    }
}

