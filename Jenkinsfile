@Library('piper-library-os')
node() {
    stage('prepare') {
        checkout scm
        setupCommonPipelineEnvironment script:this
    }
    
    stage('build') {
    mtaBuild script: this
}

}
