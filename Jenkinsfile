pipeline{
    agent any
    stages{
	 stage('SCM checkout'){
	      git 'https://github.com/ramki7/sample_maven.git'
	    }
	    stage('Compile-package'){
	       def mvnHome = tool name: 'mymaven', type: 'maven'
               sh "${mvnHome}/bin/mvn package"
		
	    }   
		
	
	}

}
