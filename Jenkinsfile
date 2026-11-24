@Library('jenkins-shared-library') _


def configMap = [
    project: "roboshop",
    component: "user",
    deploy_to : "dev",
    vesion : "1.0.0"
]

echo "here we are deploying the user"
JenkinsEKS(configMap)