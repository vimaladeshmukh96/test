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
}
stage('TEST'){
steps {
echo "this is testing zone"
}

}
}

}

