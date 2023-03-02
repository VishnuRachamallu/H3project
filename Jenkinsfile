node{
  stage ('SCM checkout'){
    git 'https://github.com/VishnuRachamallu/H3project'
  }
  stage ('commit and deploy'){
bat '''javac TestMain.java
java TestMain'''
  }

}
