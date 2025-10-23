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
                sh 'echo "Compilando proyecto.."'
            }
        }
        stage('Pruebas'){
            steps{
                sh 'echo "Ejecutando pruebas.."'
            }
        }
    }
}