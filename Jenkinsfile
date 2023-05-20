@Library('jenkins-sharedlibrary') _

pipeline {
    agent any
        stages {
            stage('pull code'){
                steps {
                gitCheckout(
                    branch: 'master',
                    url: "https://github.com/abhay9175/student-ui.git"
                )
                }
            }
        }
}
