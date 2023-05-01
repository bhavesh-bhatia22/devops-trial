pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hey there!'
                sh "chmod +x -R ./jenkins"
                sh "scripted_pipeline.sh"
            }
        }
    }
}
