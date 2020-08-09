pipeline {
agent {docker{
 image 'alpine'
}
}
stages{
stage('BuildStaging'){
steps{
echo 'creating infra for staging'
} }
stage('DeployStaging'){
steps{
echo 'deploying application on staging env'
} }
stage('ValidateStageDeployment'){
steps{
echo 'validate deployment on staging'
}
}
}
}
