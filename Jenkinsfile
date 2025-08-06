def mysum(a,b){
    sum = a + b
    sub = a - b
    println "sum of a & b is ${sum}"
    println "sub of a & b is ${sub}"
}

pipeline {
    agent any
    stages {
        stage('working with functions') {
            steps {
              script {
                mysum(200,400)
                mysub(400,240)
                }
            }
        }
    }
   }
