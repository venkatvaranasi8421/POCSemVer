pipeline {
    agent any
    environment { 
        current_version = currentVersion()
        next_version = nextVersion()
    }
    stages {
        stage ('Build') {
            steps {
              echo "Current Version of App:: ${current_version}"
              echo "Next Version of App:: ${next_version}"
            }
        }
     
    }
}
