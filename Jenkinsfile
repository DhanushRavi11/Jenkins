pipeline{
 agent any
 stages{
  stage('Git checkout'){
   steps{
    git branch: 'jenkins', url: 'https://github.com/DhanushRavi11/Jenkins.git'   

   }
  }
 
  stage('compile'){
   steps{
    sh "mvn compile"
   }
  }

  stage('build'){
   steps{
    sh "mvn package"
   }
  }
 }
}
