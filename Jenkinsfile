pipeline {
        agent any 
        tools { 
        maven 'local_maven'
        }
       
        stage("Build") {
            steps {
                 sh "mvn compile"
            }
        }       
                    
        stage("Unit test") {
            step {
                sh "mvn test"
            }
        }
        }
