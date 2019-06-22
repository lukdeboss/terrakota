
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
                sh 'ls -al /bin/terra*'
                sh 'terraform --version'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}


