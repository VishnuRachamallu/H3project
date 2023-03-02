node{
  stage ('SCM checkout'){
    git 'https://github.com/VishnuRachamallu/H3project'
  }
  stage ('commit and deploy'){
bat '''javac TestMain.java
java TestMain'''
  }
  stage('Email Notification'){
  mail bcc: '', body: 'welcome to jenkins emal alerts', cc: '', from: '', replyTo: '', subject: 'Jenkins Job status', to: 'vitturachamallu@gmail.com'
  }

}
