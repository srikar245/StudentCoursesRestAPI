pipeline {
    agent any
    stages {
        stage('Delete-dir') {
            steps {
                sh 'deleteDir(*)'
            }
        }
        stage('git-clone') {
            steps {
                sh 'git clone https://github.com/srikar245/StudentCoursesRestAPI.git'
            }
        }
        stage('Build') {
            steps {
                sh 'docker image build -t studentcourserestservice:1.0 .'
            }
        }
        stage('Test') {
            steps {
                sh 'docker image ls'
            }
        }
    }
}