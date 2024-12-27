pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/kenzzzzzzzzzz/CloudTask20216127'
            }
        }
        stage('Execute Script') {
            steps {
                bat '"C:\\Program Files\\Git\\git-bash.exe" ./script.sh'
            }
        }
    }
}
