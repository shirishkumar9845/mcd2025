pipeline {
    agent any
    parameters {
       choice choices: ['dev', 'sit', 'preprod', 'prod'], description: 'my environment', name: 'ENV'
    }
    stages {
        stage('git checkout') {
            steps {
              script {
               println  "(Hello all welcome to pipelinescripting)"
               var1=20
               println "myvar1 value is ${var1}" 
               println "value of my selected environment is ${params.ENV}"
            }
        }
    }
  }
}
