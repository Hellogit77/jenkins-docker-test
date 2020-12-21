pipeline {
    agent {
        docker {
            image 'centos'
            label 'generic'
        }
    }
    stages {
        stage("Check hostname of docker container") {
            steps {
                sh """
                    cat /etc/hostname
                """
            }
        }
    }
}