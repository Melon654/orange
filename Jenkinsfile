pipeline
{
  agent any
  stages
  {
    stage("cloning")
    {
      steps
      {
        git url
      }
    }
    stage("build")
    {
      steps
      {
        sh "javac wow.java"
      }
    }
    stage("run")
    {
      steps
      {
        sh" java wow"
      }
    }
  }
}
