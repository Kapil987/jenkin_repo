pipeline {
    agent any 
    stages {
        stage('Build **** from *** Jenkins file ****') { 
	steps { echo ' Build started'
                script {
			if (isUnix()) 	{
		echo '****** Linux OS Found ******'
         	sh "sudo yum install -y tree"
      					} 
			}
            }
		
		
        }
        stage('Test') { 
            steps { echo ' Test started'
                
            }
        }
        stage('Deploy') { 
            steps { echo ' Deploy started'
		   sh "sudo javac HelloWorld.java"
		   sh "java HelloWorld"
                 
            }
        }
    }
}
