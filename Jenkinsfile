// Declarative //
pipeline {
agent { dockerfile true }
stages {
stage('Test') {
steps {
sh 'node --version'
sh 'svn --version'
sudo sh 'ping google.com' 
}
}
}
}
// Script //
