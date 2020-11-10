node{
stage('scm checkout'){
 url: 'https://github.com/gayatrirentala/my-app'
}
 
 stage('compile-package'){
  def mvnhome = tool name: 'maven-2', type: 'maven'
  sh "${mvnhome}/bin/mvn -X clean"
}
}
