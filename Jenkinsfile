node{
stage('scm checkout'){
 url: 'https://github.com/gayatrirentala/myweb'
}
 
 stage('compile-package'){
  def mvnhome = tool name: 'maven-2', type: 'maven'
  sh "${mvnhome}/bin/mvn clean"
}
}
