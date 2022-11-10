node{
stage ('SCM Checkout'){
  
git 'https://github.com/Omkolte21/jenkinspipline/new/main'}
stage ('Compile-Package'){
  def mvnHome = tool name: 'Maven', type: 'maven'
  sh "${mvnHome}/bin/mvn package"
}
}
