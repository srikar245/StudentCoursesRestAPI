pipeline {
    agent any
    stages {
        stage('git-clone') {
            steps {
                sh 'https://github.com/srikar245/StudentCoursesRestAPI.git'
                sh 'cd Pipeline'
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

#test
