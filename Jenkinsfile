pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                git branch: 'main', url: 'https://github.com/my-empire26/JenkinsPipelineDemo'
            }
        }
    }
}
