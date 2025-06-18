pipeline {

agent any

stages {
	stage('SCM') {
		steps {
			echo "This is firs Job"
			echo $(hostname)
		}
	}
	stage('Deploy'){
		steps {
			echo "This is second Job"
			echo $(hostname)
	         	}
	}
     }
}
