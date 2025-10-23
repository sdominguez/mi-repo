pipeline{
    agent any
    stages {
        stage('Clonar codigo'){
            steps{
                git 'https://github.com/sdominguez/mi-repo.git'
            }
        }
        stage('Compilar'){
            steps{
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