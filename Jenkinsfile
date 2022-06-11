pipeline {
    agent any
	
    stages {
        stage('Build') {
		
			when{
				buildingTag()//stage should only execute if we are building from a tag
			}
		
            steps {                
                echo 'Hello World building tag'
            }
        }
    }

