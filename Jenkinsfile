// DECLARATIVE 
pilpeline {
	agent any
	stages {
		stage('Build') {
		    steps {
                echo "Build"
           }
	    }   
		stage('Test') {
		    steps {
                echo "Test"
           }
	    }   
		stage('Integration Test') {
		    steps {
                echo "Integration Test"
           }
	    }   
    }
	post {
		always {
			echo "i am very good"
		}	
		success {
			echo "i run when u sucess"	
	    }
		failure {
			echo "i run when you fail"
		}
    }	
}		
