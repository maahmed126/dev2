pipeline {			
    agent any			
    triggers {
        upstream(upstreamProjects: 'masterdev',threshold: hudson.model.Result.SUCCESS)//UNSTABLE, FAILURE, NOT_BUILT, ABORTED
    }              
stages {			
        stage('Build') {			
            steps {			
                echo 'DownstreamJob Dev2Multibranch pipeline-triggers-upstream executed'
            }			
        }			
    }	
}
