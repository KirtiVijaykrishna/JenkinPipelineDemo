pipeline{
	agent {
		dockerfile true
	}
	stages{
		stage('Examples'){
			steps{
				echo 'hello world'
				sh 'echo myCustomVar = $myCustomVar'
			}
		}
	}
}