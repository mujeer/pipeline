pipeline{
    agent any 
    stages {
        stage('present working directory') {
            steps {
                sh 'pwd'
            }
        }
        stage('mv command using'){
            steps{
                sh 'cp ${WORKSPACE}/Dockerfile ${WORKSPACE}/DOCKERFILE'
                sh 'ls'
            }
        }
    }
}
