pipeline {
    agent any
    stages {
        stage('Checkout'){
          steps {
            deleteDir()
            gitCheckout(basedir: "github.com/hirnimeshrampuresoftware/jenkinstest")
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
