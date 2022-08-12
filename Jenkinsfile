pipeline {
  stages {
    stage("reviewapp") {
      steps {
        sh(
          label: "Deploy apps",
          script: """
            docker run . -f .docker/Dockerfile
          """
        )
        }
      }
    }
  }
}
