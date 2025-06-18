pipeline {

agent any

stages {
	stage('SCM') {
		steps {
			echo "This is firs Job"
			sh 'hostname'
		}
	}
	stage('Deploy') {
		steps {
			echo "This is second Job"
			sh 'hostname'
	         	}
	}
     }
}
