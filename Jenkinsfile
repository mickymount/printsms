pipeline{
	agent any
		triggers {
			cron('H/15 * * * *')
		}
		stages{
			stage('echo'){
				steps{
					echo 'the trigger again for the final time'
				}
			}
		}
}
