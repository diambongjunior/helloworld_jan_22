pipeline {
    agent any
    
   
    tools {
        Maven
        M2_HOME
    }
    stages {
        stage('Build') {
            steps {
                mv build
            }
         stage('test') {
                mv test
            }
        }
        stage('Build') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
