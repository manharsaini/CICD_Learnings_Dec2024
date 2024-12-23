pipeline {
    agent any

    stages {
        stage('cloning repository') {
            steps {
                echo 'cloaning the code'
                git url: "https://github.com/manharsaini/CICD_Learnings_Dec2024.git",branch:"main" 
                echo 'code clone successfully'
            }
        }
        stage('executing') {
            steps {
                sh 'python3 First.py'
            }
        }
    }
}
