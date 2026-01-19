
pipeline {
    agent any

tools {
	maven 'maven3'
    }

    stages {

        stage('Checkout Code to jenkins from GitHub') 
		{
            steps {
                git branch: 'dev',
                    url: 'https://github.com/sanket0101/maven-web-application.git'
            }
        }
	}
}
 

 
>>>>>>> 7b3c111b01b3c76cc5d5dc2bf89c2c2eb64b73b8
