def pipeline

pipeline {
   agent any
libraries {
  lib('cal-lib@master')
}
	
	 stages {
	stage('Demo') {
          steps {
            pipeline = new add()
	    pipeline.call('Yuvi')
          }
        }
   }
}
