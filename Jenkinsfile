 pipeline {
agent any  

stages {
stage('build') {
steps {
hs 'ant -f build.xml -v'
}
}
}
post {
always {
archive 'dist/*jatr'
}
}
}
