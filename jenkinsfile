pipeline {
    agent { 
        label 'slave-1'
        // For custom workspace, use 'customWorkspace' inside node block
        // agent { node { label 'slave-1'; customWorkspace '/mnt/pipeline' } }
    }

    stages {
        stage("stage-1") {
            steps {
                echo "hello"
            }
        }
    }
}
