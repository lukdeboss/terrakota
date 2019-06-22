
// to komewntarz
pipeline {
<<<<<<< HEAD
    agent { label 'glowne' }
=======
    agent any
>>>>>>> d954f87ca9b5edfcb460dd0a6fd57f9c51f0c96e

    stages {
        stage('Play') {
            steps {
                echo 'robie play'
                sh 'chmod +x play.sh'
                sh './play.sh'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                echo "zakladam ze to jest tutaj"
                sh 'ls -al '
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}


