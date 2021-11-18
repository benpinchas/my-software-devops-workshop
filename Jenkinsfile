properties([pipelineTriggers([pollSCM('*/30 * * * *')])])
node {
   stage("clone") {
      git  "https://github.com/benpinchas/DevOps-0909.git"
   }

   stage("show files") {
      sh "ls -la"
   }
}
