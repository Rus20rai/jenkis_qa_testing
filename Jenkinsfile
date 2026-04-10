pipeline {
    agent any

    stages {
        stage('Salut') {
            steps {
                echo 'Salut! Pipeline-ul tau din Docker functioneaza!'
                sh 'java -version' // Verifica daca Java este prezent in container
            }
        }
        stage('Verificare Fisiere') {
            steps {
                sh 'ls -ltr' // Listeaza fisierele descarcate din GitHub
            }
        }
    }
}
