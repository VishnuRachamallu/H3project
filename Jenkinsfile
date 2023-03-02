node{
  stage ('SCM checkout'){
    git 'https://github.com/VishnuRachamallu/H3project'
  }
  stage ('compile and deploy'){
  bat '''javac TestMain.java
java TestMain'''
  }
}
