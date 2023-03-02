node{
  stage ('SCM checkout'){
    git branch: 'main', url: 'https://github.com/ktoso/maven-git-commit-id-plugin.git'
  }
  stage ('compile and deploy'){
  sh 'javac TestMain.java'
  sh 'java TestMain'
  }
}
