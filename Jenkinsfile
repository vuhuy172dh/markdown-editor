pipeline {
    agent any
    tools {
        maven 'maven'
        jdk 'jdk11'
    }
    stages {
        stage('hello') {
            steps {
                sh 'echo Hello Jenkins'
            }
        }
        stage('test casc env') {
            steps {
                echo 'JCasC env.hello: ${env.hello}'
            }
        }
   }
}
