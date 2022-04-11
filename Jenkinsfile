pipeline{
  agent any
  stages {
  stage('maven-install') {
    steps {
      Maven(globalMavenSettingsConfig: 'null', jdk: 'null', maven: 'maven3', mavenSettingsConfig: 'null') {
    sh "mvn clean install"
}
    }
  }

}


}
