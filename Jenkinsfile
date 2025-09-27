pipeline {
    agent any

    tools {
        maven 'MAVEN_HOME' 
        jdk 'JDK17'

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
