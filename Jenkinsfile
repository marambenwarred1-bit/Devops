pipeline { 
agent any
stages {
stage('Checkout Git'){
steps { checkout scm } } stage ('Build Maven') { steps {
sh 'mvn clean package'} } } }
