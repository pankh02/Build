pipeline {
  	  agent any
	{
	stages {
		stage ('checkout') {
					steps {
					checkout SCM
						}
				   }

		stage ('Build') {
					steps {
					sh 'mvn install'
						}
				}
		}
	}	
	} 
