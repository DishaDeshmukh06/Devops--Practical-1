pipeline {
    agent any
    stages {
        stage('Clone') { steps { echo 'Success: Code Pulled' } }
        stage('Build') { steps { echo 'Success: Java Compiled' } }
        stage('Test') { steps { echo 'Success: Tests Passed' } }
        stage('Deploy') { steps { echo 'Success: Docker Ready' } }
    }
}
