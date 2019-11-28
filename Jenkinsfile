def a = cal-lib.A.cal(5,6)

pipeline {
   agent any
libraries {
  lib('cal-lib@master')
}
	
	
   stages {
	stage('Demo') {
          steps {
           
            echo "Addition of 5 and 6 is ${a}"
          }
        }
   }
}
