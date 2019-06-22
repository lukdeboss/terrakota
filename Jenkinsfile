
// to komewntarz
pipeline {
    agent { label 'glowne' }
    stages {
        stage('Play') {
            steps {
                echo '=============================================================================='
                echo '=============================================================================='
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


