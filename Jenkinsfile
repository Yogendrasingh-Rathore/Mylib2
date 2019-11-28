pipeline {
   agent any
libraries {
  lib('cal-lib@master')
}
	def a = cal-lib.cal(5,6)
	
   stages {
	stage('Demo') {
          steps {
           
            echo "Addition of 5 and 6 is ${a}"
          }
        }
   }
}
