pipeline {
     agent any
     stages {
          stage("Compile") {
               steps {
                    bash "gcc src/*.c -o obj/calc"
               }
          }
          stage("Run") {
               steps {
                    bash "./obj/calc" 
               }
          }
      }
}
