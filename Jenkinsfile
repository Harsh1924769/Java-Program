pipeline{
	agent any 
	stages{
		stage('pull'){
			steps{
				sh 'git clone https://github.com/Harsh1924769/Java-Program.git '
			}
		}
		stage('compile'){
			steps{
				sh 'javac hello.java'
			}
		}
		stage('Execute'){
			steps{
				sh 'java hello.java'
			}
		}
	}
}
