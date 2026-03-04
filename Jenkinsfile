pipeline{
    agent any
    stages{
	stage('greeting'){
	    steps{
		echo "greetings from jenkins"
	    }
        }
	stage('build'){
	    steps{
		bat "mvn install"
	    }
	}
	stage('test'){
	    steps{
		bat "java -jar target/java-project4-1.4.jar"
	    }
	}
    }
}


