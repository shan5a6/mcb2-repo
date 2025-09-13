pipeline {
  // agent any/java/slave1/kubernetes/dockers
  agent any
  stages {
    stage("working with conditions") {
      steps {
        script {
          a=10
          b=20
          if (a >b) {
            println "a: ${a} is big"
          }
          else {
            println "b: ${b} is big"   
          }
        }
      }
    }
  }
}
