properties([pipelineTriggers([githubPush()])])
node('linux') {
    git url: 'https://github.com/jonkue22/infrastructure-pipeline.git', branch: 'master'
    stage('Test') {
        sh "env"
    }
}
