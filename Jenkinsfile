def add(a,b) {
  sum = a + b 
  //return (sum)
  println "sum of a:${a} && b:{b} is, ${sum}"
}
pipeline {
  // agent any/java/slave1/kubernetes/dockers
  agent any
  stages {
    stage("working with conditions") {
      steps {
        script {
          add(100,200)
          add(400,500)
          add(600)

        }
      }
    }
  }
}
