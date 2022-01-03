pipeline {
			agent any 
			stages {
				stage('BUILD') {
					steps {
						sh '''
							#!/bin/bash 
							echo "This is a fist build stage in Jenkinsfile"
							sleep 5
						'''
					}
				}
				stage('TEST1') {
					steps {
						sh 'echo "fist test stage in Jenkinsfile"; sleep 5'
					}	
				}
				stage('TEST2') {
					steps {
						sh 'echo "Second test stage in Jenkinsfile"; sleep 5'
					}	
				}
				stage('DEPLOY') {
					steps {
						sh 'echo "Final DEPLOY stage in Jenkinsfile"; sleep 5'
					}
				}
			}
		}
