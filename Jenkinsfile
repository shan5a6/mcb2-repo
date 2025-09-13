pipeline {
  // agent any/java/slave1/kubernetes/dockers
  agent any
  stages {
    stage("working with conditions") {
      steps {
        script {
          for(i=1;i<=5;i++) {
            println "my i value is: ${i}"
          }
          subjects = ["aws","azure","devops","azuredevops"]
          for(sub in subjects) {
            println "my subject is: ${sub}"
          }
          j=10
          while (j <=15) {
            println "j value is: ${j}"
            j = j + 1
            
          }
        }
      }
    }
  }
}
