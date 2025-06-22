pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                // Cloning the Git repository
                git branch: 'master', url: 'https://github.com/Bhaskark99/sbi'
            }
        }
       
        stage('Test shell scripts') {
            steps {
               sh './tel.sh'
            }
        }
    
    }
}
