node {
stage('checkout SCM') {
     git 'https://github.com/DeepthiMogaparthi/github-maven-example'
}
stage('Build') {	
 	def mvnHome = tool name: 'maven', type: 'maven'	
 	echo 'Hello World'	
 	sh "${mvnHome}/bin/mvn package"	 

   }
 }
