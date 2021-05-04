pipeline {
        agent {
                docker {
                     image 'intilery-node14:tester'
                     args "--network=ci --link selenium"
                }
        }
    stages {
        stage("Run tests") {
            steps {
                sh "echo 12311111111a11sasd1sdd111as11"
            }
        }
    }
}
