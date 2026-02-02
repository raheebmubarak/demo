pipeline {
    agent any

    stages {
        stage('git') {
            steps {
               checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/raheebmubarak/demo.git']])
            }
        }
    }
}
