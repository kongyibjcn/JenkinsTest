pipeline {
     agent any
     stages {
       stage("step1") {
            steps {
                 sh "echo step1...."
                 load "steps.groovy"
            }
       }

       stage("step2") {
            steps {
                 sh "echo step2...."
            }
       }

    }
}
