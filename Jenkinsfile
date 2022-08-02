pipeline {
    agent any
    stages {
        stage('Checkout'){
          steps {
            git branch: 'main', url: 'https://github.com/hirnimeshrampuresoftware/jenkinstest'
          }
        }
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
