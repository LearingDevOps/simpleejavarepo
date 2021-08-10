pipeline {
    agent any
    environment {
        var1 = "value1"
    }
  stages {
    stage("clone"){
      git "https://github.com/LearingDevOps/simpleejavarepo"
   }
    stage("build"){
      echo "hello"
    }
    stage("testing"){
      input {
        message 'Approve to deploy?'
      }

    }
}
