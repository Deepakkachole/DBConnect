pipeline {
    agent any
    environment {
    TEST_VAR="Fist ENV SET"    
    }
    stages {
        stage("Fist") {
            steps {
          echo "FIRST  $TEST_VAR + $env.DBName"
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

