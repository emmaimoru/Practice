pipeline{
    agent any
    stages{
        stage('1-emmanuel'){
            steps{
                checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'ad', url: 'https://github.com/emmaimoru/Practice.git']]])
            }
        }stage('2-love'){
            steps{
                sh 'lscpu'
                sh 'sudo systemctl status jenkins'
            }
        }
    }
}