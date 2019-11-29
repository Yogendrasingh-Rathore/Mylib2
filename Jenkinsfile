def pipeline

pipeline {
   agent any
libraries {
  lib('cal-lib@master')
}
	
	node('slave') {
    		pipeline = load 'Yogendrasingh-Rathore/cal-lib/vars/add.groovy'
    		pipeline.call(5,9)
	}
}
