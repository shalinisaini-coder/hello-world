pipeline {
    agent any 
    stages {
        stage( 'Build' ) {
            steps {
                bat "mvn clean -f hello-world"
            }
        }
        stage( 'Test' ) {
            steps {
                bat "mvn test -f hello-world"
                
            }
        }
        stage( 'Deploy' ) {
            steps {
                bat "mvn package -f hello-world"
                
            }
        }
    }
}
