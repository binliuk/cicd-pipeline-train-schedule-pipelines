pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                //build the app
                echo "Starting the jenkins pipeline"
                sh './gradlew build --no-daemon'
                archiveArtifacts: artifact:
            }
        }       
    }
}
