pipeline {
  /*
   * TODO: Implement pipeline stages/steps
   *   See documentation: https://www.jenkins.io/doc/book/pipeline/syntax/#stages
   */
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
