pipeline {
    agent any
    environment {
    TEST_VAR="Fist ENV SET"
    SERVER_CREDENTIALS = credentials ('server-cred')    
    }
    stages {
        stage("Fist") {
            steps {
          echo "FIRST  $TEST_VAR + $env.DBName + $SERVER_CREDENTIALS"
            }
        }
      stage("Second") {
            steps {
           echo "Second"
            }
        }

      stage("Third") {
            steps {
            echo "Third"
            }
        }

    }
}

