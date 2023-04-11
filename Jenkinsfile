@Library('my-shared-library') _

pipeline {
    agent any

    stages {
        
        
        stage('Unit Test maven') {
           // when{ expression{params.action == 'create'}}
            steps {
                script{
                    
                    mvnTest()
                }
            }
        }
    }
}
