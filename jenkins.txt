pipeline {
    agent { label 'master' }
    stages {
        stage('Dev') {
            steps {
                echo "Hello World!"
            }
        }
         stage('Test') {
            steps {
                echo "Hello World!"
            }
        }
         stage('Deploy') {
            steps {
                echo "Hello World!"
            }
        }
           
    }
}
