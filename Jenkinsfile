#!/usr/bin/env groovy

node {


	stage('check out'){
	git 'https://github.com/ziyu613/jenkinsTasks.git'
	}
	
	stage('building'){
	mvn install
	}
    
}
