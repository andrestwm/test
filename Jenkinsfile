node{
  stage ('SCM Checkout'){
    git 'https://github.com/andrestwm/test'
  }
  stage('Compile-Package'){
    sh 'mvn package'
  }
}
