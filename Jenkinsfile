node{
  stage ('SCM checkout'){
    git 'https://github.com/VishnuRachamallu/H3project'
  }
  stage ('compile and deploy'){
  javac TestMain.java
  java TestMain
  }
}
