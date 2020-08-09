pipeline {
agent { docker {
image 'alpine'
}
}
stages{
stage('BuildStaging'){
steps{
echo 'creating infra for staging'
}
}
stages{
stage('DeployStaging'){
steps{
echo 'deploying application on staging env'
}
}
stages{
stage('ValidateStageDeployment'){
steps{
echo 'validate deployment on staging'
}
}
}
}
}
}
