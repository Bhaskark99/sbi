pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                // Cloning the Git repository
                git branch: 'master', url: 'https://github.com/Bhaskark99/sbi'
            }
        }
        stage('Set Permissions') {
            steps {
                sh 'chmod +x tel.sh'
            }
        }
       
        stage('Test shell scripts') {
            steps {
               sh './tel.sh'
            }
        }
    
    }
}
