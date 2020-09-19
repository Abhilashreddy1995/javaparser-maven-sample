node{
	stage('SCM Checkout'){
	def mvnhome = tool name: 'Maven_Home' , type: 'maven'
	  git 'https://github.com/Abhilashreddy1995/javaparser-maven-sample.git'

}
	stage('Compile-Package'){
	sh 'mvn clean install'
}

}
