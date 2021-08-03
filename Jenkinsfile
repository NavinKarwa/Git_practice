pipeline {
     agent any
     stages {
          stage('Compile') {
               steps {
                    sh 'gcc calculator/src/*.c -o calculator/obj/calc'
               }
          }
          stage('Run') {
               steps {
                    sh './calculator/obj/calc' 
               }
          }
      }
}
