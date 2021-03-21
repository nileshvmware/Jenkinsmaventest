pipeline {
   agent any
   stages {
       stage("Compile and clean") {
             steps {
             sh "mvn clean complile"
            }
        }
       stage("Test") {
           steps {
              sh "mvn test"
           }
        }
       stage("Deploy") {
            steps {
               sh "mvn package"
            }
        }
    }
}
