pipeline {
    agent any
    stages {
        stage('Build') {
            steps { echo 'Compilando el código fuente...' }
        }
        stage('Test') {
            steps { echo 'Ejecutando pruebas unitarias...' }
        }
        stage('Deploy') {
            steps { echo 'Desplegando la aplicación en un entorno de prueba...' }
        }
    }
}
