pipeline {

agent any

stages {

stage('Build') {

steps {
bat 'javac HelloWorld.java'
  bat 'java -version'
//echo "HelloWorld"

}

}

stage('Run') {

steps {
bat 'java HelloWorld'
//echo "HelloWorld"
}
}
}
}
