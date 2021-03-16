pipeline {
    agent { docker { image 'maven:3.6.3-amazoncorretto-11' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
