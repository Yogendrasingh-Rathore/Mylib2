def pipeline

pipeline {
   agent any
libraries {
  lib('cal-lib@master')
}
	
	node('slave') {
    		pipeline = load 'add.groovy'
    		pipeline.call(5,9)
	}
}
