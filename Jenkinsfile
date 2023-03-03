pipeline {
    agent any
    stages {
        stage('Prueba Fn. Suma') {
            steps {
                sh '''
                    flutter doctor
                '''
            }
        }
    }
    post {
        success {
            echo "Todas las pruebas fueron realizadas correctamente!"
        }
    }
}