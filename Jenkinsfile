pipeline{
    agent any
    stages{
        stage('1-emmanuel'){
            steps{
                sh 'ps -ef'
                sh 'sudo systemctl status jenkins'
            }
        }
        stage('2-love'){
            steps{
                sh 'lscpu'
                sh 'sudo systemctl status jenkins'
            }
        }
        stage('3-ayo'){
            steps{
                 sh 'ps ef'
                 sh 'sudo systemctl status jenkins'
            }
        }
        stage('4-securityscanner'){
            steps{
                sh '/var/lib/jenkins/workspace/test group-level-ci/security.sh'
            }
        }

    }
}
