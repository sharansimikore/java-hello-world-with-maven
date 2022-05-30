pipeline
{

  agent any
  stages
  {
    stage("Gitclone")
    {
      echo "Git cloning"
      git branch: 'master', url: 'https://github.com/sharansimikore/java-hello-world-with-maven.git'
      echo "Git cloning successful"
    }
    
    stage("Build and package using maven")
    {
      echo "Building maven package"
      sh './mvnw package'
      echo "Maven package successful"
    }
    
    
  stage("Check jarfile in target")
    {
      echo "Checking jar file in target"
     
    }
  
  
  }
}
