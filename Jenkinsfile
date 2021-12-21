pipeline {			
    agent any		
        triggers {
        upstream(upstreamProjects: 'dev2Multibranch/develop',threshold: hudson.model.Result.SUCCESS)//UNSTABLE, FAILURE, NOT_BUILT, ABORTED
    }
    stages {			
        stage('Build') {			
            steps {			
                echo 'DownstreamJob pipeline-triggers-upstream executed'
            }			
        }			
    }			
}
