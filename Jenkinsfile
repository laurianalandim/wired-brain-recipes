/* Requires the Docker Pipeline plugin */
node {
    stage('Build') {
        docker.image('maven:3.8.6-openjdk-11-slim').inside {
            sh 'mvn --version'
        }
    }
}
