pipeline {
    agent any
    stages {
        stage('Checkout'){
          steps {
            checkout(basedir: "github.com/hirnimeshrampuresoftware/jenkinstest.git")
          }
        }
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
