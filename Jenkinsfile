pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
                echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
            	sh 'echo myCustomVar = $myCustomVar'
            }
        }
    }
}