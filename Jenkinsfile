pipeline {
    agent {
        docker {
            image 'python'
            label 'generic'
        }
    }
    stages {
        stage("Run HelloWorld") {
            steps {
                sh """
                    python helloworld.py
                """
            }
        }
    }
}