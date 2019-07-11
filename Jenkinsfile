node {
  stage("Git Checkout"){
    checkout(scm)
  }
  
  stage('Test') {
            sh '/usr/bin/python3 Fibonaccisequence.py'
        }
}
