node{
  stage('SCM Checkout'){
    git 'https://github.com/marwenmselmi/testJenkins'
    }
    
   stage('Compile-Package'){
     def mvnHome=tool name: '', type: 'maven'
     sh "${mvnHome}/bin/mvn package"
   }
}
