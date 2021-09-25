pipeline{
agent any

stages {

stage('BUILD'){
parallel {
stage ('BUILD1'){
steps{
sh 'this is 1st stage pipleline '
sh 'ls-lrt'
}
}

stage ('BUILD2'){
steps{
sh 'this is 1st stage pipleline '
sh 'ls-lrt'
}
}

}

steps {
sh "welcome back mahesh"
}
}
stage('SAME'){
steps {
echo "your welcome"
}

}
}
}

