pipeline {
     agent any
     stages {
          stage("Compile") {
               steps {
                    sh "gcc src/*.c -o obj/calc"
               }
          }
          stage("Run") {
               steps {
                    sh "./obj/calc" 
               }
          }
      }
}
