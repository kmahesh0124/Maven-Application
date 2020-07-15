pipeline {
    agent any

    stages {
        stage('git') {
            steps {
               git credentialsId: 'kmahesh0124', url: 'https://github.com/kmahesh0124/jenkins-pipeline.git'
            }
        }
      stage('Maveen') {
            steps {
                sh label: '', script: 'mvn clean install package'
            }
        }  
    }
}