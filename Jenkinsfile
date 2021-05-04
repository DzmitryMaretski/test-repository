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
    post {
            success {
              githubNotify context: 'something test', description: 'It works',  status: 'SUCCESS'
            }
            failure {
              githubNotify context: 'something test', description: 'This commit cannot be built',  status: 'FAILED'
            }
        }
}
