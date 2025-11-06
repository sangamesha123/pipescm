pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                bat """
                    @echo off
                    echo Hello Jenkins!
                    echo This pipeline runs on Windows.
                """
            }
        }
    }
}
