pipeline {
    agent any

    stages {
        
	     stage ('Compile Stage') {

            steps {
                //withMaven(maven : 'maven3.5.0') {
		 
		    bat 'mvn clean compile'
            //   }

			  
			  // Added new comment
		    // added new line
			}
        }
	    
        stage ('Testing Stage') {

            steps {
               // withMaven(maven : 'maven3.5.0') {
                    
		    bat  'mvn test'
               // }
            }
        }


        stage ('Install Stage') {
            steps {
              //  withMaven(maven : 'maven3.5.0') {
                    bat 'mvn install'
               // }
            }
        }
    }
}
