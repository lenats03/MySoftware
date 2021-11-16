properties([pipelineTriggers([pollSCM('* * * * *')])])
node{
    stage("clone"){
        git "https://github.com/lenats03/MySoftware.git"
    }
    stage("show files"){
    bat "dir"    
    }
}/*654*/
