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
                sh "echo 123111111a11sasdsdd111as11"
            }
        }
    }
}
