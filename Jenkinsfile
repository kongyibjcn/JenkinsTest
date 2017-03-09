pipeline {
     agent any
     stages {
       stage("step1") {
            steps {
                 sh "echo step1...."
                 def mstep = load "steps.groovy"
                 mystep.Testcall()
            }
       }

       stage("step2") {
            steps {
                 sh "echo step2...."
            }
       }

    }
}
