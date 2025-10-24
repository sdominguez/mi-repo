pipeline{
    agent any
    tools {
        nodejs 'nodejs-25'   
    }
    stages {
        stage('Clonar codigo'){
            steps{
                git 'https://github.com/sdominguez/mi-repo.git'
            }
        }
        stage('Compilar'){
            steps{
                sh 'node -v'
                sh 'npm -v'
                sh 'npm install'
            }
        }
        stage('Pruebas'){
            steps{
                sh 'npm test'
            }
        }
    }
}