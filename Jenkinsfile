pipeline {
    agent any
    stages {
        steps {
            echo 'Running build automatinon'
            sh './gradlew build --no-daemon'
            archiveArtifacts artifacts: 'dist/trainSchedule.zip'
        }
    }
}
