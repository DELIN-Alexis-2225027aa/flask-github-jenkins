pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/<votre-utilisateur>/flask-github-jenkins.git'
            }
        }
    }
}
