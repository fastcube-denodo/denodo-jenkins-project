node {
  stage('SonarQube analysis') {
    withSonarQubeEnv(installationName: 'sonar1') {
      sh 'mvn sonar:sonar'
    }
  }
}