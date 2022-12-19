def AGENT_LABEL="agent-0"

pipeline {
    agent any
    options {
        timestamps ()
    }
    stages {
        stage('stage with node-js-15') {
          steps {
              sh '''#!/bin/bash
                 cat ./test.sh
              '''
          }
        }
    }

}
