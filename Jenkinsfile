pipeline{
    agent any
    stages{
//         stage("sonar quality check"){
//             steps{
//                 script{
//                     withSonarQubeEnv(credentialsId: 'sonar-token') {
//                             sh 'mvn clean verify sonar:sonar'
                            
//                     }
                    
//                       timeout(time: 1, unit: 'HOURS') {
//                       def qg = waitForQualityGate()
//                       if (qg.status != 'OK') {
//                            error "Pipeline aborted due to quality gate failure: ${qg.status}"
//                       }
//                     }
//                 }   
//             }
//         }
        
        stage("code test"){
             steps{
                 script{
                     echo 'code test'
                 }
             }
        }  
        
           stage("Docker Image build"){
             steps{
                 script{
                     echo 'code test'
                 }
             }
        } 
        
           stage("Docker image push"){
             steps{
                 script{
                     echo 'code test'
                 }
             }
        } 
    }
    post{
        always{
            echo "========always========"
        }
        success{
            echo "========pipeline executed successfully ========"
        }
        failure{
            echo "========pipeline execution failed========"
        }
    }
}
