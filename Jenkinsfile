node{
   stage('SCM checkout'){
     git 'https://github.com/ramki7/sample_maven.git'
   }
   stage('Compile-package'){
    sh 'mvn package'
   }
}
