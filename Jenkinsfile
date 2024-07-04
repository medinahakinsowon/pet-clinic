pipeline {
   agent any
       stages{
           stage('validate'){
              steps{
                 sh 'mvn validate'
              }
           }
           stage('compile'){
                 sh 'mvn compile'
           }



       }
}
