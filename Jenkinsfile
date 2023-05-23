@Library('jenkins-sharedlibrary') _

pipeline {
    agent any
        stages {
            stage('pull code') {
                steps {
                gitcheckout(
                    branch: 'master',
                    url: "https://github.com/abhay9175/student-ui.git"
                )
                }
            }
            stage('unit test mvn') {
                steps {
                    script{
                        mvnTest()
                }
            }
            stage('integration test mvn') {
                steps {
                    script{
                        mvnintegrationTest()
                    }    
                }
            }
        }
    }
}
