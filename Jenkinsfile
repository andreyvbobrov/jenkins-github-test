node {
  stage('Checkout') {
    checkout scm
    sh "ls -la"
    sh "False"
  }
  stage('Syntax') {
    sh "pylint *.py"
    sh "env"
  }
}
