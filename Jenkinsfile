pipeline {
    agent any
    

    stages {
        stage ('Compile Stage') {

            steps {
                
                    sh 'mvn clean compile'
                }
            
        }

        stage ('Testing Stage') {

            steps {
                
                    sh 'mvn test'
                }
            
        }

        
        stage ('Echo Branch') {

            steps {
                
                    echo "This is master branch"
                }
            
        }
    }
}
