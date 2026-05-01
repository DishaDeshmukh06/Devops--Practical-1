pipeline {
    agent any
    stages {
        stage('Clone') { steps { echo 'Code Pulled' } }
        stage('Build Java') { steps { echo 'Java Compiled' } }
        stage('Run Java') { steps { echo 'App Running' } }
        stage('Build Docker Image') { steps { echo 'Docker Image Ready' } }
    }
}
