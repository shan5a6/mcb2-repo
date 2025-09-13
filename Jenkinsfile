pipeline {
  // agent any/java/slave1/kubernetes/dockers
  agent any
  parameters {
    choice choices: ['dev', 'prod'], description: 'Enter the environment details', name: 'ENV'
  }   
  environment {
    JAVA_VERSION = "14"
  }
  
  stages {
    stage("working with variable") {
      steps {
        script {
          subject = "jenkins scripting"
          println "my subject  name is ${subject}"
          println "my selected environment is ${params.ENV}"
          println "my selected java version is ${env.JAVA_VERSION}"
        }
      }
    }
  }
}
