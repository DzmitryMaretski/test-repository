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
                s "echo 123111111asasdsdd111as11"
            }
        }
    }
}
