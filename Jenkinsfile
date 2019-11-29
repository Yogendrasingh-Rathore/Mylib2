pipeline {
   agent any
libraries {
  lib('cal-lib@master')
}
	
	
   stages {
	stage('Demo') {
          steps {
	    add call(5,6)           
            echo "Addition of 5 and 6 is ${a}"
          }
        }
   }
}
