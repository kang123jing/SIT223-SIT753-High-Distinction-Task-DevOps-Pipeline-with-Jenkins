pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'git clone..'
                git branch: 'main', credentialsId: '871db934-4eb4-406c-a64d-7867ceb86291', url: 'https://github.com/kang123jing/sit725-2023-t1-prac8.git'
                sh 'pwd'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
        stage('Release') {
            steps {
               echo 'Release....'
            }
        }
    }
}
