 @Library('my-shared-library') _
 pipeline {
    agent any

    stages {
        stage('git checkout') {
            steps {
            gitCheckout{
                branch: "main",
                url: "https://github.com/samapika99/mrdevops_java_app.git"
            }
            }
        }
    }
}           