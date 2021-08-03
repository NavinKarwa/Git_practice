pipeline {
     agent any
     stages {
          stage('Compile') {
               steps {
                    sh 'gcc calculation/src/*.c -o calculation/obj/calc'
               }
          }
          stage('Run') {
               steps {
                    sh './calculation/obj/calc' 
               }
          }
      }
}
