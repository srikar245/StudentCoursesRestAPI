pipeline {
    agent any
    stages {
        stage('git-clone') {
            steps {
                sh 'https://github.com/srikar245/StudentCoursesRestAPI.git'
                // Change file permisson
                sh "chmod +x -R ./jenkins"
                // Run shell script
                sh "./jenkins/script/scripted_pipeline_ex_2.sh"
                 }
                           }
           }
}
#test
