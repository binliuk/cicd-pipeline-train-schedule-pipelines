pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                //build the app
                ./gradlew build --no-daemon
            }
        }       
    }
}
