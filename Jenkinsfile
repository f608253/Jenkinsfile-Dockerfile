// Declarative //
pipeline {
agent { dockerfile true }
stages {
stage('Test') {
steps {
sh 'node --version'
sh 'svn --version'
sh 'df -h' 
sh 'find / -size +1k -print'  
}
}
}
}
// Script //
