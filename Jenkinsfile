pipeline {
    agent {
        kubernetes {
            defaultContainer 'jnlp'
        }
    }
    stages {
        stage('Test Stage') {
            steps {
                echo "this will be triggered!."
            }
        }
        stage() {
            steps {
                echo "another stage"
            }
        }
    }
}