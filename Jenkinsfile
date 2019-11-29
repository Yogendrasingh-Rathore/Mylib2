def pipeline

pipeline {
   agent any
libraries {
  lib('cal-lib@master')
}
	
	node('slave') {
    		pipeline = load 'cal-lib.add.groovy'
    		pipeline.call(5,9)
	}
}
