node {
  stage('cloning maven project')
  {
    git 'https://github.com/Sharath-yp25/mavenproject.git'
  }
  stage('Building maven project')
  {
    sh 'mvn package'
  }
}
