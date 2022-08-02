pipeline {
    agent any
    stages {
        stage('Checkout'){
          steps {
            gitCheckout(basedir: "src/github.com/hirnimeshrampuresoftware/jenkinstest")
            stash allowEmpty: true, name: 'source', useDefaultExcludes: false
          }
        }    
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
