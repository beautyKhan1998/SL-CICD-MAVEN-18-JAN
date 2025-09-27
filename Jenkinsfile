pipeline {
    agent any

    tools {
        maven 'MAVEN_HOME'   // Configure Maven installation in Jenkins → Global Tool Configuration

    }

    stages {
        stage('Welcome Stage') {
            steps {
                echo 'Welcome to Jenkins Pipeline'
            }
        }
        stage('clean Stage') {
            steps {
                bat 'mvn clean'
            }
        }
        stage('Final Stage') {
            steps {
                echo 'sucessfully build'
            }
        }

     }

}
