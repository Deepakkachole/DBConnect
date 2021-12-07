def gv 
pipeline {
    agent any
    environment {
    TEST_VAR="Fist ENV SET"
    }
    stages {
        stage("Fist") {
            steps {
                script {
                    gv.testpp()
                }
            }
        }
      stage("Second") {
            steps {
           script {
                    gv.buildApp()
                }
            }
      }

      stage("Third") {
            steps {
             script {
                    gv.deployApp()
                }
            }
    }
}

