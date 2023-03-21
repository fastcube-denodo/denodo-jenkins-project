node {
  stage('SonarQube analysis') {
    withSonarQubeEnv(installationName: 'server-sonar') {
      sh 'mvn org.sonarsource.scanner.maven:sonar-maven-plugin:3.7.0.1746:sonar'
    }
  }
}