pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Compilando el código...'
                // Si usas Maven o Gradle, agrega el comando correspondiente aquí
                // Ejemplo: sh 'mvn clean install'
                // -- //
            }
        }

        stage('Test') {
            steps {
                echo 'Ejecutando pruebas...'
                // Comando para ejecutar pruebas
                // Ejemplo: sh 'mvn test'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Desplegando aplicación...'
                // Agrega el comando para desplegar
                // Ejemplo: sh './deploy.sh'
            }
        }
    }
}