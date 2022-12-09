pipeline {
    any agente {
        label 'worker-linux'
    }

    stages {

        stage ('Build') {
            steps {
                sh 'mvnw'
            }
        }
        stage ('Test') {
            steps {
                sh 'mvnw.cmd'
            }
        }
        stage ('Deploy') {
            steps {
                sh pom.xml
            }
        }

    }
}