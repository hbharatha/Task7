pipeline
{

agent any
triggers {
upstream 'devProject, testProject,'
}
stages {
stage('FIRST-JOB'){
steps{
git 'https://github.com/rubeenashaik/task7.git'
}
}
stage('Example') {
steps {
echo 'Hello World'
}
}
}
}
