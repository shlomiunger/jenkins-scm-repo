properties([pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("clone"){
        git "https://github.com/shlomiunger/jenkins-scm-repo.git"
    }
    stage("show files"){
        bat "dir"

    }
}

// Testing SCM trigger
