node('slave'){
  gradle4 = tool 'gradle4'
  stage('Checkout') {
    checkout SCM
  }
  stage('Build') {
    sh 'gradle build'
  }
}
