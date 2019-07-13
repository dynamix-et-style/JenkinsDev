pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        sh '''pipeline {
   agent any
    
   stages {
      stage(\'Say Hello\') {
         steps {
            echo \'Hello World!\'   
         }
      }
   }
}'''
        }
      }
    }
    environment {
      Excercise1 = ''
    }
  }