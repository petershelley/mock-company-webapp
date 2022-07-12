pipeline {
   stages {
    stage ('Build') {
      steps {
        sh './gradlew assemble'
        echo 'Hello pooper'
      }
    }
    
    stage ('Test') {
      steps {
        sh './gradlew test'
        echo 'Hello pooper'
      }
    }
   }
}
