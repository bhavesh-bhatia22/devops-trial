pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hey there!'
                sh "chmod +x -R ./jenkins"
                sh "./jenkins/script/scripted_pipeline.sh"
            }
        }
    }
}
