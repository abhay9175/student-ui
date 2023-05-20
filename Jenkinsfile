@Library('jenkins-sharedlibrary-mrdevopsproject') _

pipeline {
    agent any
        stages {
            stage('pull code'){
                steps {
                gitcheckout(
                    branch: 'master',
                    url: "https://github.com/abhay9175/student-ui.git"
                )
                }
            }
        }
}
