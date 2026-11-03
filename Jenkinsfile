pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                // Compiles the Java source file into bytecode (hello.class)
                sh 'javac hello.java'
            }
        }
        
        stage('Execute & Verify') {
            steps {
                // Runs the compiled Java class file and prints to the console
                sh 'java hello'
            }
        }
    }
}

