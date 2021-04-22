@Library('piper-lib-os') _
node() {
     stage('init') {
           cleanWs()
           checkout scm
           setupCommonPipelineEnvironment script:this
        }
}
