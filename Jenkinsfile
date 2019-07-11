node (linux-slave){
  stage("Git Checkout"){
    checkout(scm)
  }
  
  stage('Test') {
            sh '/usr/bin/python3 Fibonaccisequence.py'
        }
}
