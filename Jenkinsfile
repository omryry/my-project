properties([pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("clone"){
        git branch: 'main', url: 'https://github.com/omryry/my-project.git'
    }
    stage("show files"){
        sh "ls -ltr"
    }
}
