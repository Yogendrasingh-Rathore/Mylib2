pipeline {
   agent any
libraries {
  lib('cal-lib@master')
}
	
	
   stages {
	stage('Demo') {
          steps {
	    echo "Addition of 5 and 6 is "
	    add call(5,6)           
            
          }
        }
   }
}
