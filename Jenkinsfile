pipeline{
	agent any
	stages{
		stage('Building the Code'){
			steps{
			
				echo 'Running the Build Automation'
				sh './gradlew build --no-daemon'
				archiveArtifacts artifacts: "dist/trainSchedule.zip"
			}
		}
	}
}
