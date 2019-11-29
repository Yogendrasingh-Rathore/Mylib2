def pipeline

pipeline {
   agent any
libraries {
  lib('cal-lib@master')
}
	
	 stages {
	stage('Demo') {
          steps {
            pipeline = new cal-lib.add()
	    pipeline.call('Yuvi')
          }
        }
   }
}
