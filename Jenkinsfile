pipeline {
    agent any
    stages {
        stage('git-clone') {
            steps {
                 git branch: 'main', credentialsId: 'e3df5ff8-c6dd-4b02-bc9e-a7e4fbd0d57f', url: 'https://github.com/srikar245/StudentCoursesRestAPI.git'
            }
        }
        stage('Build') {
            steps {
                 sh 'cd  Pipeline@tmp'
                 sh 'docker image build -t studentcourserestservice:1.0 .'
            }
        }
    }
}

//test
