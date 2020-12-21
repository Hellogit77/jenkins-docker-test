pipeline {
    agent {
        dockerfile true
        label 'generic'
    }
    stages {
        stage("Run HelloWorld") {
            steps {
                sh """
                    python helloworld.py
                """
            }
        }
        stage("Test request") {
            steps {
                sh """
                    python requestgoogle.com
                """
            }
        }
    }
}