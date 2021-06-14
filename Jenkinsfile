node {
  stage ('SCM Checkout'){
    git 'https://github.com/divyarekham/maven-hello-world'
  }
  stage ('Compile-Package'){
    sh 'mvn package'
  }
}
