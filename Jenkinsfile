@Library('shared-library2') _
pipeline{
    agent any
    stages{
         stage("build"){
            steps{
                script{
                    build()
                }
            }   
        } 
       stage("Test"){
            steps{
                script{
                    echo "test"
                }
            }   
        }
    }   
}
